<script>
  import Nav from "../components/Nav.svelte";
  import Header from "../components/Header.svelte";

  export let segment;
</script>

<Header />
<Nav {segment} />

<main>
  <slot />
</main>

<style>
  main {
    position: relative;
    max-width: 56em;
    background-color: inherit;
    padding: 2em;
    margin: 0 auto;
    box-sizing: border-box;
  }
</style>
