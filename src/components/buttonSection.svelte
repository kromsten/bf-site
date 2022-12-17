<script lang="ts">
    import { base } from '$app/paths';
    import Button from "./button.svelte";
</script>

<section class="d-flex gap-4">
    <Button src="{base}/Buttons/Mint/Mint.png" href="{base}/" />
    <Button src="{base}/Buttons/What/What.png" href="{base}/what"/>
    <Button src="{base}/Buttons/FAQ/FAQ.png" href="{base}/faq"/>
    <Button src="{base}/Buttons/Contact/Contact.png" href="{base}/" />
</section>