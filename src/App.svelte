<script lang="ts">
	  import { Router, Route, Link } from "svelte-routing";
	  import About from "./pages/about.svelte";
	  import Landing from "./pages/landing.svelte";
		import UI_UX from "./pages/ui_ux.svelte";
		import Illustrations from "./pages/illustrations.svelte";
		import Branding from "./pages/branding.svelte";

	  export let url = "";
</script>

<Router>
	<nav>
		<Link to="/"></Link>
		<Link to="about">About me</Link>
		<Link to="ui_ux">UI/UX</Link>
		<Link to="illustrations">Illustrations</Link>
		<Link to="branding">Branding</Link>
	</nav>

	<main>
		<Route path="/" component={Landing}></Route>
		<Route path="about" component={About}/>
		<Route path="ui_ux" component={UI_UX}/>
		<Route path="illustrations" component={Illustrations}/>
		<Route path="branding" component={Branding}/>
	</main>
</Router>

<style>

	nav {
		width: 100%;
		padding: 4rem 0;
		display: flex;
		justify-content: flex-end;
	}

	@media screen and (max-width: 900px) {
		nav {
			padding: 8rem 0 0;
		}
	}

</style>