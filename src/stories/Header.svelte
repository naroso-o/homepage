<script>
	import './header.css';
	import logo from '$lib/assets/logo.png';
</script>

<header>
	<div class="storybook-header">
		<a class="logo-button" href="/">
			<img src={logo} width="32" height="32" alt="logo" />
			<h4>NAROSO</h4>
		</a>
		<nav class="navigation">
			<a href="/projects">Projects</a>
			<a href="/notes">Notes</a>
		</nav>
	</div>
</header>
