<script>
import { onMount } from "svelte";

  import { Router, Route, Link, navigate } from "svelte-routing";

  import Aa from "./branding/aa.svelte";
  import BluePineapple from "./branding/blue-pineapple.svelte";
  import Eisloft from "./branding/eisloft.svelte";
  import PetitFamily from "./branding/petit-family.svelte";
  import VermontSeventeen from "./branding/vermont-seventeen.svelte";

  let { from } = { from: { pathname: "/branding/blue-pineapple" } };

  onMount(() => {
    navigate(from.pathname, { replace: true });
  })

</script>

<Router>

  <nav class="branding-subnav">
    <Link to="blue-pineapple">Blue Pineapple</Link>
    <Link to="petit-family">Petit Family</Link>
    <Link to="a-a">AA</Link>
    <Link to="eisloft">Eisloft</Link>
    <Link to="vermont-seventeen">Vermont17teen</Link>
  </nav>

  <main>
    <div class="left-corner-gradient"></div>
    <div class="background-layer"></div>
    <div class="right-corner-gradient"></div>

    <Route path="blue-pineapple" component={BluePineapple} />
    <Route path="petit-family" component={PetitFamily}/>
    <Route path="a-a" component={Aa}/>
    <Route path="eisloft" component={Eisloft}/>
    <Route path="vermont-seventeen" component={VermontSeventeen}/>
  </main>
</Router>

<style></style>