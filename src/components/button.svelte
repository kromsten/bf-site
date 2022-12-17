<script lang="ts">
    export let src : string;
    export let href : string;


    const sections = src.split('/');
    const alt = sections[sections.length - 1].split('.')[0];
    
</script>

<a {href}>
    <img {src} {alt}>
</a>

<!-- <button style="--url:url({url})" /> -->

<style>

    img {
        max-height: 160px;
    }

    img:hover {
        transform: scale(1.2);
    }

    /* button {
        background: transparent;
        background-image: var(--url);
        background-repeat: no-repeat;
        background-size: 100%;
        height: 180px;
        width: 220px;
        border: 0;
    }

    button:hover {
        cursor: pointer;
    } */
</style>