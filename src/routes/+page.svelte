<script>
	// import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="Birdland Game" content="A game where you are a lizard and you go to an island of birds." />
</svelte:head>

<section>
		<span class="welcome">
			<picture>
				<source srcset="favicon.png" type="image/webp" />
				<a href="https://www.instagram.com/birdlandgame?igsh=NTc4MTIwNjQ2YQ%3D%3D">
					<img src="favicon.png" alt="Birdland Logo" />
				</a>
			</picture>
		</span>
<!--	<Counter />-->
</section>


<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
		height: 100vh;
		background-image: url('static/TempSplashArt.jpg');
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100%;
		height: auto;
		padding: 0;
	}

	.welcome img {
		max-width: 100%;
		height: auto;
	}
</style>
