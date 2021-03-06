<script>
  export let title
</script>

<section class="phone">
  <div class="title">{title}</div>
  <slot/>

  <div class="slide-up">
    App drawer
  </div>
</section>

<style>
  .phone {
		font-family: sans-serif;
		font-size: 0.8rem;
    border: solid 2px #ccc;
		padding: 5px;
		border-radius: 20px;
    height: 20rem;
    background: var(--background-color);
		box-shadow: 1px 1px var(--shadow-color);
    color: var(--text-color);
    position: relative;
    width: 160px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
	}

  .slide-up {
    background: #ddd;
		border-radius: 10px 10px 15px 15px;
    height: 40px;
    animation: slide-up 0.3s ease-in;
    animation-delay: 1s;
    animation-iteration-count: 1;
    animation-fill-mode: forwards;
  }

  @keyframes slide-up {
    from {
      height: 10px;
    }
    to {
      height: 200px;
    }
  }
</style>

