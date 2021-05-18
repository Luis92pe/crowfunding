<script>
	import Button from "./components/atoms/Button.svelte";
	import HeaderCard from "./components/molecules/HeaderCard.svelte";
	import CounterCard from "./components/molecules/CounterCard.svelte";
	import AboutCard from "./components/organisms/AboutCard.svelte";

	export let name;
</script>

<main>
    <section class="header-container" />
    <section class="content-container">
        <HeaderCard/>
        <CounterCard/>
        <AboutCard/>
    </section>

</main>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Commissioner:wght@400;500;700&display=swap');

	main {
        background-color: ghostwhite;
        font-size: 16px;
        font-family: 'Commissioner', sans-serif;
		text-align: center;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

    .header-container {
        height: 230px;
        background: url('/images/image-hero-mobile.jpg');
        background-attachment: initial;
        background-repeat: no-repeat;
        background-size: contain;
    }

    .content-container {
        width: 90%;
        margin: -50px auto;
    }

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
