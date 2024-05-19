<script>
  import "../app.css";
</script>

<div class="w-full font-mono dark">
  <div class="mt-10 p-4 max-w-3xl mx-auto">
    <div class="text-3xl">
      Privacy Corner @ <a href="https://ethberlin.org" class="hover:underline"
        >ETHBerlin04</a
      >
    </div>
    <div class="mt-10">
      <slot />
    </div>
  </div>
</div>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.black);
    color: theme(colors.white);
  }
</style>
