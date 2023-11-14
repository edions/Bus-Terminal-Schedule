<script>
	import Header from '../../lib/components/Header.svelte';
	import { page } from '$app/stores';
	import '../../styles.css';

	const { route } = $page;
	console.log(route);
	console.log("Hello")
  </script>
  
  <div class="app">
	{#if route.id !== '/admin/login'}
	 <Header /> 
	 {/if}

	<main>
	  <slot />
	</main>
  </div>
  