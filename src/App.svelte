
<script>
  import { Router, Route, link } from 'svelte-routing';
  import Home from './Home.svelte';
  import Contacto from './pages/Contacto.svelte';
</script>
<main>
  <Router>
      <Route path="/" component={Home} exact/>
      <Route path="/contacto" component={Contacto}/>
  </Router>

</main>
