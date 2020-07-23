<script lang="ts">
  import Header from "./Header.svelte";
</script>

<main>
  <!---
		Error: Type 'number' is not assignable to type 'string'. (ts)
		<Header name={1} />
	-->
  <Header name={'test'} />
  <p>Svelte ❌ Typescript</p>
</main>
