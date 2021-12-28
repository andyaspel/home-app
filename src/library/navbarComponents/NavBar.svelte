<script>
  import Logo from "./Logo.svelte";
</script>

<nav class="nav-bar">
  <div class="logo"><Logo /></div>
  <header class="page-title"><h1>page title</h1></header>
  <div class="nav-link">
    <a href="/">link button</a>
    <a href="/about">link button</a>
    <a href="/contacts">link button</a>
  </div>
</nav>

<style>
  .nav-bar {
    box-sizing: inherit;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-content: center;
    padding: 0.4em;
    border: 1px solid hsl(256, 62%, 58%);
    color: hsl(60, 16%, 87%);
    background-color: hsl(240, 91%, 17%);
  }
  .page-title h1 {
    margin: 0;
    padding-bottom: 0.1em;
    font-size: 3.2rem;
  }
  .logo {
    align-self: center;
    padding: 0.2em;
  }
  .nav-link {
    display: flex;
    flex-direction: column;
    align-self: center;
    padding: 0.2em;
    border: 0.2rem solid hsl(226, 63%, 84%);
  }
  a {
    color: hsl(60, 16%, 87%);
    padding-bottom: 0.3em;
  }
  a:hover {
    color: hsl(90, 42%, 48%);
    text-decoration: none;
  }
  a:visited {
    color: hsl(258, 19%, 89%);
    border: 0.2rem solid hsl(192, 82%, 32%);
  }
</style>
