<script>
  import logo from './assets/svelte.png'
  import Counter from './lib/Counter.svelte'
</script>

<main class="text-center p-4">
  <img src={logo} alt="Svelte Logo" class="w-16 h-16" />
  <h1>Hello World!</h1>

  <Counter />

  <p class="w-max-10 m-3">
    Visit <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte
    apps.
  </p>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
    the officially supported framework, also powered by Vite!
  </p>
</main>

