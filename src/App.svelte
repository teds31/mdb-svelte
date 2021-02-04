<script>
	export let name;
	import DropdownNav from './components/DropdownNav.svelte';
	import Input from './components/Input.svelte';
	// import HomeNav from './components/HomeNav.svelte'
</script>

<main>
	<!-- <HomeNav /> -->
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<div class="container">
		<DropdownNav />
	</div>
	<div class="container">
		<div class="row justify-content-center">
			<div class="col-lg-6">
			</div>
		</div>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>