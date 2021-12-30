<script>
  export let searchText;
</script>

<form action="">
  <label for="search-bar" aria-label="search-bar" />
  <input
    type="search"
    name="search-bar"
    id="search-bar"
    placeholder="Search"
    bind:value={searchText}
  />
</form>

<style>
  form {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 2rem auto;
    padding: 0.6em 0;
    width: 45rem;
    border: 0, 1em solid hsla(270, 50%, 40%, 0.808);
    background-color: hsl(270, 14%, 78%);
    border-radius: 0.5em;
    box-shadow: 0.15rem 0.2rem 0.1rem 0.1rem rgba(255, 0, 245, 0.151);
  }
  form input {
    width: 92%;
    font-size: 1.3rem;
    font-weight: 500;
    color: hsl(243, 95%, 8%);
    padding: 0.2em 0.3em;
    margin: 0;
    border: none;
    border-radius: 0.25em;

    /* align-self: center; */
  }
</style>
