<script>
  import NavBar from "./library/navbarComponents/NavBar.svelte";
  import SearchBar from "./library/formComponents/SearchBar.svelte";
  let name = "fuck!! it works!";
  // let searchText = "searchText";
  let  searchText ;
  let test =[];
  test.push(searchText)
  
  $: console.log(test);
 
</script>

<NavBar />
<main>
  <h1>Bollocks!!</h1>
  <p>{name}</p>
  <SearchBar {searchText} />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
    letter-spacing: 1.2rem;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
