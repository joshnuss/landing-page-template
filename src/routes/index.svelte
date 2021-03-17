<script>
  import SubscribeForm from '@/components/SubscribeForm.svelte'
  import { Screen } from 'svelte-preview-ui'
  import Phone from '@/components/Phone.svelte'
</script>

<svelte:head>
  <title>Landing page template</title>
</svelte:head>

<div class="top">
  <header>
    <a class="logo" href="/">LOGO</a>
    <a href="#subscribe" class="subscribe">
      <span>Sign up</span>
      <svg width=20 xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
      </svg>
    </a>
  </header>

  <section class="hero">
    <h1>The best infrastructure for the web.</h1>
    <p>Don't waste time with the other guys solution. There's a <strong>better</strong> way.</p>

    <div class="box">
      <Screen title="index.html" class="screen">
      </Screen>
      <div class="phone">
        <Phone title="chrome">
        </Phone>
      </div>
    </div>
  </section>
</div>

<main>
  <SubscribeForm/>
</main>

<style>
  .top {
    background: var(--header-background);
    background-size: cover;
    background-position: bottom;
    width: 100%;
  }
  header {
    padding: 1rem 1.5rem;
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

  .logo {
    color: var(--background-color);
  }
  .hero h1, .hero p {
    text-align: left;
  }

  h1 {
    color: var(--background-color);
    font-weight: 700;
    font-size: 3rem;
  }
  .hero p {
    font-size: 1.7rem;
    letter-spacing: -1px;
    line-height: 1.9rem;
    color: #666;
  }
  .box {
    margin-top: 40px;
    margin-bottom: -80px;
    width: calc(100vw - 4rem);
    position: relative;
  }
  .phone {
    position: absolute;
    right: -20px;
    top: 10px;
    transform: scale(0.9);
  }

  :global(.screen) {
    min-height: 400px;
  }
</style>
