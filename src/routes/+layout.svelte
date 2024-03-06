<script>
  import '../app.css'
</script>

<svelte:head>
  <title>Heat Haze Games 🔥</title>
</svelte:head>

<main class="flex flex-col flex-grow w-full mx-auto max-w-5xl h-full gap-16">
  <header class="flex gap-10 items-center justify-between border-b border-white pb-8">
    <a href="/">
      <img src="/heathaze.webp" class="max-w-40 aspect-auto" alt="Heat Haze Games logo" /></a
    >
    <div class="flex gap-10 items-center">
      <a href="https://store.steampowered.com/app/2512850/Tales_of_the_Laser_Knights"
        ><img src="/steam.svg" alt="Steam" class="w-10" /></a
      >
      <a href="https://www.tiktok.com/@realdenzi"
        ><img src="/tiktok.svg" alt="TikTok" class="w-9" /></a
      >
      <a href="https://www.youtube.com/@heathazegames5701"
        ><img src="/youtube.svg" alt="YouTube" class="w-11" /></a
      >
      <a href="https://www.instagram.com/heathazegames/"
        ><img src="/instagram.svg" alt="Instagram" class="w-10" /></a
      >
      <a href="https://discord.gg/nvNMYtn5H4"
        ><img src="/discord.svg" alt="Discord" class="w-9" /></a
      >
    </div>
  </header>
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
