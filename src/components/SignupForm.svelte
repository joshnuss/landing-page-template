<form>
  <div class="fields">
    <input type="email" name="email" placeholder="E-mail address" required/>
    <button>Subscribe</button>
  </div>
</form>

<style>
  form {
    margin: 100px 0;
    border-radius: var(--border-radius);
  }
  form:focus-within {
    outline: solid 1px red;
  }
  .fields {
    display: flex;
    place-self: center;
    align-items: center;
    justify-content: center;
  }
  input, button {
    font-size: 1rem;
    padding: 1rem 1rem;
  }

  input {
    border-radius: var(--border-radius) 0 0 var(--border-radius);
    border-right: none;
  }
  button {
    border-radius: 0px var(--border-radius) var(--border-radius) 0px;
    background-color: var(--accent-color);
  }
</style>
