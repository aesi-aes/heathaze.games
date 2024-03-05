<script>
  import '../app.css'
</script>

<svelte:head>
  <title>Heat Haze Games 🔥</title>
</svelte:head>

<main class="flex flex-col flex-grow w-full mx-auto max-w-7xl h-full gap-8 ">
  <slot />
</main>

<style>
  :global(body) {
    background: rgb(12, 24, 62);
    background-repeat: no-repeat;
    background-image: url('/banner.webp'),
      radial-gradient(at bottom, rgb(3, 129, 171) 0%, rgb(12, 24, 62) 100%);
    background-position: bottom;
    background-size: contain;
  }
</style>
