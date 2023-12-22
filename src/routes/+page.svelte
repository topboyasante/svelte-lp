<script>
	import Conversion from '../components/Conversion.svelte';
import FaQs from '../components/FAQs.svelte';
	import Hero from '../components/Hero.svelte';
	import ProductDescription from '../components/ProductDescription.svelte';
	import Reviews from '../components/Reviews.svelte';
</script>

<main class="flex flex-col">
	<Hero />
	<ProductDescription />
	<Reviews />
	<FaQs />
    <Conversion/>
</main>
