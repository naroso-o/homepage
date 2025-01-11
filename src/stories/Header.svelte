<script>
	import './header.css';
	import logo from '$lib/assets/logo.png';
</script>

<header>
	<div class="storybook-header">
		<a class="logo-button" href="/">
			<img src={logo} width="32" height="32" alt="logo" />
		</a>
		<nav class="navigation">
			<a href="/projects">Projects</a>
			<a href="/notes">Notes</a>
			<a href="/about">About me</a>
		</nav>
	</div>
</header>
