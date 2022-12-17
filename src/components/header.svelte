<script>
	import ButtonSection from "./buttonSection.svelte";
    import LogoSection from "./logoSection.svelte";
</script>

<nav class="d-flex justify-content-between align-items-center px-5 py-3">
    <LogoSection />
    <ButtonSection />
</nav>


<style>
    nav {
        width: 100%;
        z-index: 3;
        background: transparent;
        position: fixed;
    }
</style>