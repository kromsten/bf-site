<script>
    import Header from "../components/header.svelte";
	import Footer from "../components/footer.svelte";
</script>

<Header />
<slot />
<Footer />

<style>
    :global(body) {
        margin: 0;
    }
</style>