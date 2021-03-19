<form id="subscribe">
  <h2>Beta access</h2>
  <p>The service will launch at $10/month. Everyone on the beta list will receive a 25% discount.</p>
  <div class="fields">
    <input type="email" name="email" placeholder="E-mail address" required/>
    <button>Subscribe</button>
  </div>
</form>

<style>
  form {
    border-top: solid 3px var(--text-color);
    padding-top: 36px;
  }
  h2, p {
    margin: 1rem 2rem;
  }
  .fields {
    display: flex;
    place-self: center;
    align-items: center;
    justify-content: center;
  }
  input, button {
    font-size: 1.2rem;
    padding: 0.8rem 0.5rem;
  }

  input {
    border-radius: var(--border-radius) 0 0 var(--border-radius);
    border-right: none;
    max-width: 200px;
  }
  button {
    border-radius: 0px var(--border-radius) var(--border-radius) 0px;
    background-color: var(--accent-color);
    border-color: black;
    color: var(--background-color);
  }
</style>
