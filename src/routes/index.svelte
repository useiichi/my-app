<script lang='ts'>
	import Markdown from 'svelte-exmarkdown';
	let md = '# Hello world!';
</script>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<textarea bind:value={md} />
<Markdown {md} />
