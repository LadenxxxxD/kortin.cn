<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
  import Poetry from './lib/Poetry.svelte'
</script>

<header></header>
<main>
  <h1>Hi, it's me.</h1>

  <div class="card">
    <Counter />
  </div>

  <div class="card">
    <Poetry />
  </div>

  <!-- <p>
    Check out my other sites <a href="https://github.com/sveltejs/kit#readme" target="_blank">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p> -->
</main>
<footer>
<div>
    <p>
      The site is powered by Vite + Svelte!
    </p>
    <a href="https://vitejs.dev" target="_blank"> 
      <img src="/vite.svg" class="powered-logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank"> 
      <img src={svelteLogo} class="powered-logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <p class="beian">
    <a href="https://github.com/sveltejs/kit#readme" target="_blank">苏ICP备2021038623号</a>
  </p>
</footer>

<style>
  .powered-logo {
    height: 2em;
    padding: 1em;
    will-change: filter;
  }
  .powered-logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .powered-logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }

  footer {

  }

  .beian  a{
    font-size: 0.9em;
    color: #888;
  }
  .beian a:hover {
    color: #ddd;
  }
</style>