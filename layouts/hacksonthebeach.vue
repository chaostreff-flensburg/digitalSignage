<template>
	<section id="hacksonthebeach">
		<nuxt/>

		<img src="~/assets/img/hacksonthebeach/wortmarke.svg" alt="" id="hotb-logo" class="absolute">
		<img src="~/assets/img/hacksonthebeach/loetschirm.svg" alt="" id="hotb-schirm" class="absolute">
	</section>
</template>

<style>
@import url(https://fonts.googleapis.com/css?family=Arvo:400,700);

#hacksonthebeach {
	width: 100vw;
	height: 100vh;

	margin: 0 !important; 
  padding: 0 !important;

	font-family: 'Arvo', serif;

	background-image: url('~/assets/img/hacksonthebeach/flagoutline.svg');
	background-size: 210%;
	background-position: center;
	background-position-y: 53.5%;
}

.absolute {
	position: absolute;
	height: 2.5cm;
	width: auto;
}

#hotb-logo {
	bottom: 0.75cm;
	left: 1cm;
	height: 15%;
}

#hotb-schirm {
	bottom: 0.75cm;
	right: 1cm;
	height: 22.5%;
}
</style>
