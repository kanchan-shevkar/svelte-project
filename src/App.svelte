<script>
	import { Router, Route } from 'svelte-routing';
	import Nav from './lib/components/Nav.svelte';
	import Landing from './pages/Landing.svelte';
	import About from './pages/About.svelte';
	import Contact from './pages/Contact.svelte';
	import './app.css';
</script>

<Router>
	<Nav />
	<Route path="/" component={Landing} />
	<Route path="/about" component={About} />
	<Route path="/contact" component={Contact} />
</Router>
