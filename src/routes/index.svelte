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
      <div class="phone-wrapper">
        <Phone title="chrome" class="phone">
        </Phone>
      </div>
    </div>
  </section>
</div>

<section class="features">
  <h2>Features</h2>

  <article>
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 15.546c-.523 0-1.046.151-1.5.454a2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.701 2.701 0 00-1.5-.454M9 6v2m3-2v2m3-2v2M9 3h.01M12 3h.01M15 3h.01M21 21v-7a2 2 0 00-2-2H5a2 2 0 00-2 2v7h18zm-3-9v-2a2 2 0 00-2-2H8a2 2 0 00-2 2v2h12z" />
    </svg>
    <div class="content">
      <h3>Feature #1</h3>
      <p>lorem ipsum</p>
    </div>
  </article>

  <article>
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
    </svg>
    <div class="content">
      <h3>Feature #2</h3>
      <p>lorem ipsum</p>
    </div>
  </article>

  <article>
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 15.546c-.523 0-1.046.151-1.5.454a2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.701 2.701 0 00-1.5-.454M9 6v2m3-2v2m3-2v2M9 3h.01M12 3h.01M15 3h.01M21 21v-7a2 2 0 00-2-2H5a2 2 0 00-2 2v7h18zm-3-9v-2a2 2 0 00-2-2H8a2 2 0 00-2 2v2h12z" />
    </svg>
    <div class="content">
      <h3>Feature #3</h3>
      <p>lorem ipsum</p>
    </div>
  </article>

  <article>
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
    </svg>
    <div class="content">
      <h3>Feature #4</h3>
      <p>lorem ipsum</p>
    </div>
  </article>
</section>

<main>
  <SubscribeForm/>
</main>

<footer>
  <a href="https://twitter.com/joshnuss">
    <svg height=30 xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><title>Twitter icon</title><path fill=currentColor d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"/></svg>
  </a>
  <a href="https://github.com/joshnuss">
    <svg height=30 viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>GitHub icon</title><path fill=currentColor d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/></svg>
  </a>
</footer>

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
    width: var(--container-width);
    margin: 0px auto;
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
    padding: var(--hero-padding);
    margin: 0 auto;
    box-sizing: border-box;
    text-align: center;
    width: var(--container-width);
  }
  main {
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
    font-size: var(--heading-font-size);
  }
  .hero p {
    font-size: var(--sub-heading-font-size);
    letter-spacing: -1px;
    line-height: 1.9rem;
    color: #666;
  }
  .box {
    margin-top: 40px;
    margin-bottom: -80px;
    position: relative;
    padding: var(--hero-box-padding);
  }
  .phone-wrapper {
    position: absolute;
    right: -20px;
    top: var(--hero-phone-top);
    transform: scale(0.9);
  }

  :global(.phone) {
    height: var(--hero-phone-height) !important;
    width: var(--hero-phone-width) !important;
  }

  footer {
    display: flex;
    gap: 10px;
    padding: 1rem 1rem;
    justify-content: center;
    margin: 3rem 0 1rem;
  }

  .features {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    margin: var(--main-margin);
    margin-top: 100px;
    margin-bottom: 100px;
    width: var(--container-width);
  }

  .features h2 {
    margin-bottom: 1rem;
  }
  .features h3 {
    font-weight: bold;
  }
  .features p {
    margin: 0;
  }

  .features article {
    display: flex;
    gap: 1rem;
  }
  .features .content {
    flex: 1;
  }

  .features svg {
    color: #555;
    width: 30px;
    align-self: flex-start;
  }

  :global(.hero .screen) {
    height: var(--hero-screen-height);
    width: var(--hero-screen-width);
    text-align: left;
    font-size: 1.5rem !important;
  }
</style>
