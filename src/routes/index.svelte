<script>
	import Metatags from "../components/metatags.svelte";
	import Quote from "../components/quote.svelte";
</script>

<style>
	p {
		text-align: center;
	}
</style>

<Metatags />

<svelte:head>
	<style>
		body {
			color: #404040;
			background: #dce1e1;
		}
	</style>
</svelte:head>

<Quote />
<p>Follow me on Twitter <a href="https://twitter.com/mikenikles">@mikenikles</a> for updates on this project.</p>
