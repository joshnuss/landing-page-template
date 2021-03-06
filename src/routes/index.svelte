<script>
  import SubscribeForm from '@/components/SubscribeForm.svelte'
</script>

<svelte:head>
  <title>Landing page template</title>
</svelte:head>

<div class="top">
  <header>
    <a href="/">LOGO</a>
    <a href="#subscribe" class="subscribe">
      <span>Subscribe</span>
      <svg width=20 xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
      </svg>
    </a>
  </header>

  <section class="hero">
    <h1>Best infrastructure for the web.</h1>
    <p>When your're building a techonology product you need good stuff. Right?</p>
  </section>
</div>

<main>
  <SubscribeForm/>
</main>

<style>
  .top {
    background: var(--header-color);
    width: 100%;
  }
  header {
    padding: 1rem 1rem;
    display: flex;
    place-items: center;
    justify-content: space-between;
  }
  header a.subscribe {
    display: flex;
    background: #fff4;
    border-radius: 25px;
    text-decoration: none;
    padding: 0.3rem 1rem;
    color: var(--background-color);
    gap: 2px;
  }
  header .subscribe span {
    display: block;
  }
  .hero {
    position: relative;
    padding: 5rem 1.5rem;
    margin: 0 auto;
    box-sizing: border-box;
    text-align: center;
  }
  main {
    display: flex;
    justify-content: center;
  }

  .hero h1, .hero p {
    text-align: left;
  }

  h1 {
    font-weight: 500;
    font-size: 2.5rem;
  }
  .hero p {
    font-size: 1.5rem;
  }
</style>
