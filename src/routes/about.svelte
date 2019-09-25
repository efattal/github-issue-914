<script context="module">
	export async function preload({params, query}) {
		return {
			foo: query.foo
		}
	}
</script>

<script>
	export let foo;
</script>

<svelte:head>
	<title>About</title>
</svelte:head>

<h1>About this site</h1>

<p>This is the 'about' page. There's not much here.</p>

<p>Foo: {foo}</p>