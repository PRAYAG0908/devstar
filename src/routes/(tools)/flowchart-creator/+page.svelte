<script lang="ts">
	import Intro from '$lib/Intro.svelte';
	export let data;

</script>

<Intro heading={data.meta.title} description={data.meta.description} />

<div class=" flex border-4 border-blue-900 dark:border-white mx-32 rounded-lg ">
	<div class="border-2 text-white p-2  w-2/5  lg:w-1/4 sm:w-full bg-[#111827]">
		<div class="shapes ">
			<h3 class="text-center text font-bold  border">Shapes</h3>
			<ul>Rectangle</ul>
			<ul>Square</ul>
			<ul>Circle</ul>
			<ul>Triangle</ul>
			<ul>Oval</ul>
			<ul>Diamond</ul>
			<ul>Parallelogram</ul>
		</div>
		<div class="tool">
			<h3 class="text-center font-bold border">Tools</h3>
			<section>Brush</section>
			<seciton>Eraser</seciton>
			<seciton>Pencil</seciton>
			<seciton>Colors</seciton>
			<section class="color">
				<input name="colour" class="bg-red-700" value="red" type="radio">
				<input name="colour"class="bg-blue-700" value="blue" type="radio">
				<input name="colour"class="bg-green-700" value="green" type="radio">
				<input name="colour"class="bg-black" value="black" type="radio">
				<input name="colour"class="bg-yellow-200" value="yellow" type="radio">
				<input name="colour"class="bg-white-200" value="white" type="radio">
			</section>
		</div>
		<div class=" py-1">
		<div class="function grid grid-cols-2 gap-1  ">
			<button class="border rounded-lg  px-1">Undo</button><button class="border rounded-lg px-1">Redo</button></div>
		<div class="eraseall border px-1 border rounded-lg my-1 text-center"><button >Erase All</button></div>
		<div class="border px-1 border rounded-lg text-center"><button>Export</button></div>
		</div>
		
	</div>
	
	<canvas class=" bg-white w-3/5  lg:w-3/4 sm:w-full">The Flow Chart Generator module is designed to automate the creation of visual flowcharts, diagrams, and process maps. It streamlines the process of converting textual or logical information into easy-to-understand visual representations. Users can input data, define relationships, and choose from various shapes and connectors to generate professional-looking flowcharts, enhancing communication and decision-making in a visual format.</canvas>
</div>














