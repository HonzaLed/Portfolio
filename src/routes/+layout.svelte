<script>
  import "../app.css";
</script>

<nav>
  <a href="/">home</a>
  <a href="/about">about</a>
</nav>

<slot />

<style lang="postcss">
  :global(body) {
    @apply bg-white dark:bg-black;
  }
</style>
