<script>
  import Avatar from "./lib/Avatar.svelte";
  import Social from "./lib/Social.svelte";
  import Footer from "./lib/Footer.svelte";
</script>

<main>
  <Avatar />
  <h1>Hello world!</h1>
  <p class="desc">
    <span>Lenny Ochanda</span> is a web developer, Commerce (Finance) student at Kenyatta University, musician, avid reader and defender of human rights.
    He can be found on:
  </p>
  <Social />
</main>
<footer>
  <Footer />
</footer>

<style>
  .desc {
    color: rgb(136, 136, 136);
  }
  
  span {
    color: rgb(33, 53, 71);
  }

  footer {
    position: sticky;
    width: 100%;
    bottom: 0;
    box-sizing: border-box;
    display: flex;
    justify-content: center;
  }
</style>
