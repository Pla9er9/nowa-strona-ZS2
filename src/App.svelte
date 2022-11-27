<script lang="ts">
  import Footer from "./components/Footer.svelte";
  import Navbar from "./components/Navbar.svelte";
  import LeftBox from "./components/LeftBox.svelte";
  import Menu from "./components/Menu.svelte";
  //Pages
  import Contact from './pages/Contact.svelte';
  import Docs from './pages/Docs.svelte'
  import ESchool from './pages/ESchool.svelte'
  import Library from './pages/Library.svelte'
  import Matura from './pages/Matura.svelte'
  import News from './pages/News.svelte'
  import Projects from './pages/Projects.svelte'
  import Rodo from './pages/Rodo.svelte'
  import School from './pages/School.svelte'
  import Start from './pages/Start.svelte'

  $: MenuVisibility = false

  function cmv() {
    MenuVisibility = !(MenuVisibility)
    console.log("Menu visibility: " + MenuVisibility)
  }
  
  var pages: string[] = ["dokumenty", "biblioteka","matura","projekty","kontakt","rodo","monitoring","aktualnosci"]

  var pageTitle: string

  const queryString = window.location.search;
  const urlParam = new URLSearchParams(queryString);
  const p = urlParam.get('p')

  if (pages.includes(p))
    pageTitle = p.charAt(0).toUpperCase() + p.slice(1);
  else if (p === "szkola")
    pageTitle = "Szkoła"
  else if (p === "eszkola")
    pageTitle = "e-Szkoła"
  else if (p === "aktualnosci")
    pageTitle = "Aktualności"
  else 
    pageTitle = ""

</script>

<main>
  <div id="app0">
    <Navbar on:changeMenuVisibility={cmv}/>
    <LeftBox visibility={MenuVisibility}>
      <Menu />
    </LeftBox>
    <div id="container">
      <h2>{pageTitle}</h2>

      {#if p === "szkola"}
        <School></School>

      {:else if p === "eszkola"}
        <ESchool></ESchool>

      {:else if p === "dokumenty"}
        <Docs></Docs>

      {:else if p === "biblioteka"}
        <Library></Library>

      {:else if p === "matura"}
        <Matura></Matura>

      {:else if p === "projekty"}
        <Projects></Projects>

      {:else if p === "kontakt"}
        <Contact></Contact>

      {:else if p === "rodo"}
        <Rodo></Rodo>

      {:else if p === "aktualnosci"}
        <News></News>
      {:else}
        <Start></Start>
      {/if}
    </div>
  </div>
</main>
<style>
  #app0 {
    display: flex;
    position: relative;
    min-height: 100%;
  }

  #container{
    margin-top: 100px;
    width: 100vw;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #container h2 {
    color: #ff9f10;
    align-self: flex-start;
    text-indent: 130px;
    font-size: 40px;
  }

  @media only screen and (max-width: 680px){
    #container h2 {
      text-indent: 0px;
      align-self: center;
    }
  }
</style>