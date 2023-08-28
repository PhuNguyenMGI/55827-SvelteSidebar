<script>
	import Sad from '$lib/images/sad-outline.svg';
	import Happy from '$lib/images/happy-outline.svg';
	import CodeSlash from '$lib/images/code-slash-outline.svg';
	import Sync from '$lib/images/sync-outline.svg';
	import Sidebar from '$lib/components/Sidebar.svelte';
	const data = [
		{
			name: 'Sad',
			src: Sad,
			item: 'item 1 🤔',
		},
		{
			name: 'Happy',
			src: Happy,
			item: 'item 2 🤔',
		},
		{
			name: 'Code Slash',
			src: CodeSlash,
			item: 'item 3 🤔',
		},
		{
			name: 'Sync',
			src: Sync,
			item: 'item 4 🤔',
		}
	]
</script>

<section>
	<Sidebar data={data} />
	<div class="novel ml-[60px] px-6">
		<h1 class="chapter-title">Chapter 1: The Lorem Ipsum Novel</h1>
		<p class="paragraph">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod, lacus nec vestibulum
			tempor, lectus nunc sollicitudin tortor, in lacinia mauris mi nec tellus.
		</p>
		<p class="paragraph">
			Sed gravida feugiat est eu efficitur. Fusce hendrerit ex non est tempor, ut maximus sapien
			fringilla. Nam sit amet justo id quam auctor varius.
		</p>
		<p class="paragraph">
			Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Donec
			ullamcorper enim et nisl consectetur, in porttitor purus ultricies.
		</p>
	</div>
</section>

<style></style>
