<script>
  import Main from "./pages/Main.svelte";
  import Router from 'svelte-spa-router';
  import NotFound from "./pages/NotFound.svelte";
  import "./css/styles.css";

  const routes = {
    '/':Main,
    "*":NotFound
  }
</script>

<Router routes={routes}/>

<style>
  div {
    color: green;
  }
</style>
