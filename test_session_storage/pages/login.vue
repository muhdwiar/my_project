<template>
<div align="center" class="py-5">
  <div class="w-25 py-5">
    <b-form @submit="onSubmit" @reset="onReset">

      <b-form-group id="input-group-2" label="Your Name:" label-for="input-2">
        <b-form-input
          id="input-2"
          v-model="form.name"
          required
          placeholder="Enter name"
        ></b-form-input>
      </b-form-group>

      <b-button type="submit" variant="primary">Submit</b-button>
      <b-button type="reset" variant="danger">Reset</b-button>
    </b-form>
  </div>
</div>
</template>

<script>
  
  export default {
    data() {
      return {
        form: {
          name: '',
        },
      }
    },

    methods: {
      onSubmit(evt) {
        evt.preventDefault()
        sessionStorage.setItem('myCat',this.form.name)
        location.href = "http://localhost:3000/form_subcribe"
      },
      onReset(){
      }
    }
  }
</script>