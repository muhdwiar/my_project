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

		<div align="center">
			<div class="pb-5"></div>
			<h1 class="text-info">PROFILE</h1>
			<hr class="w-25 bg-info">
			<div class="profile-box-style pt-2">
			<b-card class="text-left shadow" border-variant="info">
				<b-row>
					<b-col cols="1"></b-col>
					<b-col cols="4">NAME</b-col>
					<b-col cols="6">: Muhamad Dwi Arifianto</b-col>
				</b-row>

				<b-row>
					<b-col cols="1"></b-col>
					<b-col cols="4">ADDRESS</b-col>
					<b-col cols="6">: Jl. Ijen Boulevard No. 44</b-col>
				</b-row>

				<b-row>
					<b-col cols="1"></b-col>
					<b-col cols="4">DISTRICT</b-col>
					<b-col cols="6">: Pujon</b-col>
				</b-row>

				<b-row>
					<b-col cols="1"></b-col>
					<b-col cols="4">CITY</b-col>
					<b-col cols="6">: Batu</b-col>
				</b-row>

				<b-row>
					<b-col cols="1"></b-col>
					<b-col cols="4">PROVINCE</b-col>
					<b-col cols="6">: Jawa Timur</b-col>
				</b-row>

				<b-row>
					<b-col cols="1"></b-col>
					<b-col cols="4">POSTAL CODE</b-col>
					<b-col cols="6">: 56789</b-col>
				</b-row>

				<b-row>
					<b-col cols="1"></b-col>
					<b-col cols="4">EMAIL</b-col>
					<b-col cols="6">: dwi@raya.com</b-col>
				</b-row>
			</b-card>
			<b-button variant="info" class="mt-5 shadow">EDIT PROFILE</b-button>
			</div>
		</div>

		<!-- FOOTER -->
		<div fluid class="text-center mt-5 bg-info footer-height-0 text-light fixed-bottom">
			<b>@2019</b>
		</div>
	</section>
</template>