<script>
  import { onMount } from "svelte";
  import Footer from "./footer.svelte";
  import Head from "./head.svelte";
  import Header from "./header.svelte";
  import Login from "./login.svelte";

  export let content, layout, allContent, allLayouts, env, user;

  let hash;
  onMount(async () => {
    hash = window.location.hash;
  });
</script>

<html lang="en">
  <Head title={content?.fields?.meta?.title} {env} {...content.fields} />
  <body id="top">
    <Header />
    <main class="main">
      {#if user && $user.isAuthenticated}
        <svelte:component this={$user.menu} {user} bind:content />
      {/if}
      <Login bind:hash {user} />
      <svelte:component
        this={layout}
        {...content.fields}
        {allContent}
        {allLayouts}
        {content}
      />
    </main>
    <Footer />
    <a href="." id="scroll-top"><i class="far fa-angle-double-up" /></a>
  </body>
</html>
