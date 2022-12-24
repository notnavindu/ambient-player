<script>
	let paused = true;
</script>

<main class="h-screen w-full bg-black flex items-center justify-center p-5">
	<div class=" fixed blur-3xl contrast-150 opacity-50">
		<video autoplay loop class="w-full max-w-full m-auto" bind:paused muted>
			<source src="ambient_sample.mp4" type="video/mp4" />
			<track kind="captions" />
		</video>
	</div>

	<div class="w-full max-w-4xl rounded-lg overflow-hidden z-50">
		<video autoplay loop bind:paused muted class="shadow-2xl">
			<source src="ambient_sample.mp4" type="video/mp4" />
			<track kind="captions" />
		</video>
	</div>
</main>
