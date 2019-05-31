<template>
	<section>
		<!-- top nav -->
		<div class="shadow" position="top">
			<b-navbar variant="info" type="dark">
			    <b-navbar-nav>
			      	<b-nav-item href="#">HOME</b-nav-item>
			      	<b-nav-item href="#">PRODUCT</b-nav-item>
			      	<b-nav-item href="#">PROFILE</b-nav-item>
			      	<b-nav-item href="#">HELP</b-nav-item>
			    </b-navbar-nav>
		  	</b-navbar>
		</div>

		<div align="center" class="py-3">
			<b-form-group class="my-5 w-50">
	          <b-input-group>
	            <b-form-input v-model="searchword" placeholder="Type to Search"></b-form-input>
	          </b-input-group>
	        </b-form-group>
			<b-table class="mb-5 w-75" striped bordered  :items="IDKota" :fields="fields"></b-table>
		</div>

		<!-- FOOTER -->
		<div fluid class="text-center mt-5 bg-info footer-height-0 text-light fixed-bottom">
			<b>@2019</b>
		</div>
	</section>
</template>

<script>
	import gql from 'graphql-tag';
	import DATA_KOTA from '~/query/data_kota.gql';

	export default {
		
		data(){
	    	return {
				fields: [{key:'id',sortable:true},{key:'nama',sortable:true},{key:'kota',sortable:true},{key:'provinsi',sortable:true},{key:'kodepos',sortable:true}],
				searchword:'',
							
			}
	    },

	    apollo: {
			IDKota: {
				query : DATA_KOTA,
				variables() {
					return{
						search: this.searchword,
					}
				}
			}
	    },
	}
</script>