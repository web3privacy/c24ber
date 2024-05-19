<script>
  import "../app.css";
  import Index from "$lib/../../../pages/index.md";
</script>

<svelte:head>
  <title>Privacy Corner @ ETHBerlin04</title>
</svelte:head>

<div class="w-full dark">
  <div class="mt-10 p-4 max-w-3xl mx-auto">
    <div class="mb-10">
      <a href="https://web3privacy.info"
        ><img
          src="https://web3privacy.info/logo.svg"
          class="w-[144px] h-[40px]"
        /></a
      >
    </div>
    <div class="flex items-center gap-4">
      <div class="text-3xl font-mono">
        Privacy Corner @ <a href="https://ethberlin.org" class="hover:underline"
          >ETHBerlin04</a
        >
      </div>
    </div>
    <div class="mt-10 mb-10 w-full">
      <div class="prose prose-invert">
        <Index />
      </div>
    </div>
  </div>
</div>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.black);
    color: theme(colors.white);
  }
</style>
