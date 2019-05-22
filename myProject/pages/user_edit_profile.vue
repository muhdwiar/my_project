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

		 <div align="center" class="my-4">
			 <b-container>
				<b-card title="EDIT PROFILE" class="trans shadow">
					<hr>
					<b-form-input type="text" placeholder="Name" class=" mb-2"></b-form-input>
					<b-form-input type="text" placeholder="Address" class="mb-2"></b-form-input>
					<b-form-input type="text" placeholder="District" class=" mb-2"></b-form-input>
					<b-form-input type="text" placeholder="City" class=" mb-2"></b-form-input>
					<b-form-input type="text" placeholder="Province" class=" mb-2"></b-form-input>
					<b-form-input type="text" placeholder="Postal Code" class=" mb-2"></b-form-input>
					<b-form-input type="text" placeholder="Email" class="mb-2"></b-form-input>
					<hr>
				</b-card>

				<b-button variant="info" class="shadow mt-3">CHANGE</b-button>

			</b-container>
	    </div>

		<!-- FOOTER -->
		<div fluid class="text-center mt-5 bg-info footer-height-0 text-light fixed-bottom">
			<b>@2019</b>
		</div>
	</section>
</template>