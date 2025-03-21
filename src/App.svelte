<script>
	import Navbar from './components/Navbar.svelte';
	import HeroSection from './components/HeroSection.svelte';
	import Dashboardpreview from './components/Dashboardpreview.svelte';
</script>

<main>
	<Navbar />
	<HeroSection />
	<Dashboardpreview />

</main>

<style>

  :global(body) {
    background-color: #F6F5F8;
    margin: 0;
    padding: 0;
	font-family: 'Inter', sans-serif; 
  }
  

  :global(html) {
    background-color: #F6F5F8;
  }
</style>