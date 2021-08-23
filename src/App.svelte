<script lang="ts">
	  import { Router, Route, Link } from "svelte-routing";
	  import About from "./pages/about.svelte";
	  import Landing from "./pages/landing.svelte";

	  export let url = "";
</script>

<Router>
	<nav>
		<Link to="about" class="link">About me</Link>
		<Link to="/" class="link"></Link>
	</nav>

	<main>
		<Route path="/" component={Landing}></Route>
		<Route path="about" component={About}/>
	</main>
</Router>

<style>

	nav {
		float: right;
		padding: 4rem;
	}

</style>