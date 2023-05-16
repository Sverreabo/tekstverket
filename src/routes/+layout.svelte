<script>
    import "$lib/app.css";
    import Header from "$lib/Header.svelte";
</script>

<main>
    <div class="container">
        <Header />
    </div>
    <slot />
</main>
