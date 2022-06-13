<script>
    import "../app.css";
    import Nav from "./nav.svelte";
</script>

<main class="container mx-auto max-w-xs h-screen relative">
    <slot />
    <Nav />
</main>
