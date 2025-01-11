<script>
	import orbit from '$lib/assets/orbit.png';
	import planets from '$lib/assets/planets.png';
	import sign from '$lib/assets/sign.png';
</script>

<div class="banner-container">
	<span class="title">Hello, 2025!</span>
	<span class="description">Naroso's new release plan</span>
	<img src={orbit} alt="orbit" width="400px" />
	<img src={planets} alt="planets" width="400px" />
	<img src={sign} alt="sign" width="80px" />
</div>

<style>
	.banner-container {
		padding: 2em 4em 2em 4em;
		background-color: white;
		border: 1px solid #5b5b5b;
		border-radius: 4px;
	}

	.banner-container .title {
		display: block;
		font-size: 64px;
	}

	.banner-container .description {
		display: block;
		font-size: 32px;
	}
</style>
