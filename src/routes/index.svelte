<script>
  import SignupForm from '@/components/SignupForm.svelte'
</script>

<svelte:head>
  <title>Landing page template</title>
</svelte:head>

<div class="top">
  <header>
    LOGO
  </header>

  <section class="hero">
    <h1>The <strong>best</strong> copy on earth.</h1>
    <h2>The best tagline <em>on earth</em>.</h2>
  </section>
</div>

<main>
  <SignupForm/>
</main>

<style>
  .top {
    background: var(--header-color);
    width: 100%;
  }
  header {
    padding: 1rem 1rem;
  }
  .hero {
    position: relative;
    padding: 5rem 0.5rem;
    margin: 0 auto;
    box-sizing: border-box;
    text-align: center;
  }
  main {
    display: flex;
    justify-content: center;
  }

  h1 {
    font-size: 2.5rem;
  }
  h2 {
    font-size: 1.5rem;
  }
</style>
