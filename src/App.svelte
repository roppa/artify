<script>
  import Header from './header/Header.svelte'
  import About from './about/About.svelte'
  import Gallery from './gallery/Gallery.svelte'
  import Contact from './contact/Contact.svelte'
  import Footer from './footer/Footer.svelte'
</script>

<main>
	<Header />
	<About />
	<Gallery />
	<Contact />
	<Footer />
</main>

<style>

  main {
    text-align: center;
		margin: 0 auto;
		display: flex;
		flex-direction: column;
}

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
