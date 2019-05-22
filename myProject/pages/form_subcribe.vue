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

		<!-- header -->
		
			<div class="pb-5 text-black-shadow delete-item">
			  <b-card
			  	class="shadow-lg text-center text-light"
			    overlay
			    img-src="http://www.creativesmiles.com.au/wp-content/uploads/2019/01/Blue-Triangles-l.jpg"
			    img-alt="Card Image"
			    >
			    <b-card-title class="header-text">
			    	<b>PT MALANG RAYA</b>
			    </b-card-title>
			    <b-card-text>
			      <b>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod</b>
			    </b-card-text>
			  </b-card>
			</div>

			<b-container fluid class="w-75 py-3">
				<h2 class="text-center text-info">ABOUT</h2>
				<hr class="w-25 mx-auto bg-info mb-5">
				<p>
					Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
					quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
					consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
				</p>

			</b-container>

			<!-- subcribe menu -->
			<div align="center">
			<div class="py-3">
				<div class="text-center text-info">
					<h2>PRODUCT</h2>
					<hr class="w-25 mx-auto bg-info mb-5">
					<h5> Some quick example text to build on the card and make up the bulk of the card's content</h5>	
				</div>

				<b-button variant="outline-info" class="button-style py-5 mx-3 mt-3 shadow">
					<b-container>
						<h4>PACKAGE 1</h4>
						<h6 class="my-4">Rp 18.000/bulan</h6>
						<hr>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
						tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
						</p>
					</b-container>
				</b-button>

				<b-button variant="outline-info" class="button-style py-5 mx-3 mt-3 shadow">
					<b-container>
						<h4>PACKAGE 2</h4>
						<h6 class="my-4">Rp 50.000/bulan</h6>
						<hr>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
						tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
						</p>
					</b-container>
				</b-button>

				<b-button variant="outline-info" class="button-style py-5 mx-3 mt-3 shadow">
					<b-container>
						<h4>PACKAGE 3</h4>
						<h6 class="my-4">Rp 200.000/bulan</h6>
						<hr>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
						tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
						</p>
					</b-container>
				</b-button>
			</div>
		</div>

		<!-- FOOTER -->
		<div position="bottom" fluid class="text-center mt-5 bg-info footer-height text-light">
			CONTACT US
			<br>
			PHONE : 0855-5555-5555
			<br>
			EMAIL : malang@raya.com
			<br>
			<br>
			<b>@2019</b>
		</div>
	</section>
</template>