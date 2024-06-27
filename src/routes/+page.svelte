<script>
	import backgroundImage from '$lib/penguin.jpg';

	let bgImage = backgroundImage;
</script>

<div
	class="relative h-screen bg-cover bg-center"
	style="background-image: url({bgImage}); background-opacity-50"
>
	<div
		class="absolute inset-0 flex flex-col items-center justify-center bg-black bg-opacity-50 text-center"
	>
		<p class="text-3xl font-semibold text-white">Welcome to Saturn 🪐</p>
		<p class="text-white">
			<a href="/login" class="text-primary hover:cursor-pointer hover:underline">login</a>
			/
			<a href="/signup" class="text-primary hover:cursor-pointer hover:underline">signup</a>
		</p>
	</div>
</div>
