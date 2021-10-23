<script lang="ts">
	  import { Router, Route, Link } from "svelte-routing";
	  import About from "./pages/about.svelte";
	  import Landing from "./pages/landing.svelte";
		import UI_UX from "./pages/ui_ux.svelte";
		import Illustrations from "./pages/illustrations.svelte";
		import Branding from "./pages/branding.svelte";
		import Redirect from "./pages/redirect.svelte";
		import BluePineapple from "./pages/branding/blue-pineapple.svelte";

		function getProps({ location, href, isPartiallyCurrent, isCurrent }) {
    const isActive = href === "/" ? isCurrent : isPartiallyCurrent || isCurrent;

    // The object returned here is spread on the anchor element's attributes
    if (isActive) {
      return { class: "active" };
    }
    return {};
  }
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
		<Route path="/" component={Landing}/>
		<Route path="about" component={About}/>
		<Route path="ui_ux" component={UI_UX}/>
		<Route path="illustrations" component={Illustrations}/>
		<Route path="branding/*" component={Branding}>
			<Redirect to="/blue-pineapple" />
		</Route>
		<Route path="blue-pineapple" component={BluePineapple}/>
	</main>
</Router>

<style>

	nav {
		width: 100%;
		padding: 4rem 0;
		display: flex;
		justify-content: flex-end;
	}

	:global(a[aria-current="page"]) { font-weight: bold; }

	@media screen and (max-width: 900px) {
		nav {
			padding: 8rem 0 0;
		}
	}

</style>