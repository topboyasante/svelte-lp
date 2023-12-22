<script>
    import { openModal } from '../store/index';
</script>

<header class="flex flex-col relative z-[20]">
	<div class="max-w-screen-xl mx-auto w-full flex items-center justify-between p-4 py-6">
		<a href="/"><h1>Gym<span class="text-indigo-400">Streak</span></h1></a>
        <button on:click={() => ($openModal = true)} class="md:hidden grid place-items-center">
            <i class="fa-solid fa-bars"></i>
        </button>
        <nav class="hidden md:flex items-center gap-4 lg:gap-6">
            <a class="duration-200 hover:text-indigo-400 cursor-pointer" href="#product">Product</a>
            <a class="duration-200 hover:text-indigo-400 cursor-pointer" href="#reviews">Reviews</a>
            <a class="duration-200 hover:text-indigo-400 cursor-pointer" href="#faqs">FAQs</a>
            <button class="specialBtn">
                <p>Start Free Today</p>
            </button>
        </nav>
	</div>
</header>
