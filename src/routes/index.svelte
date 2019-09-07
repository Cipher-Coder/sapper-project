<script>
  import Header from "../components/Header.svelte";
  import Card from "../components/Card.svelte";

  let intro = "Lets Practice Some Skills!!";

  const pkg = {
    title: "Math Facts!",
    src: "../img/kidBlackboard.jpg",
    altText: "Cartoon of child in front of blackboard",
    aHref: "#",
    desc: "Practice Your Math!"
  };

  const art = {
    title: "Vocabulary",
    src: "../img/boyReading.jpg",
    altText: "Cartoon of child reading book",
    aHref: "#",
    desc: "Practice Your Spelling!"
  };
</script>

<style>
  h1,
  p {
    text-align: center;
    margin: 0 auto;
  }

  h1 {
    font-size: 2.8em;
    text-transform: uppercase;
    font-weight: 700;
    margin: 0 0 0.5em 0;
    color: #000000;
  }

  p {
    margin: 1em auto;
  }

  .menu-container {
    margin: auto;
    text-align: center;
  }

  @media (min-width: 480px) {
    h1 {
      font-size: 4em;
    }
  }
</style>

<svelte:head>
  <title>Aiden &amp; Zoie's Homework</title>
</svelte:head>

<Header />

<h1>{intro}</h1>

<div class="menu-container">
  <Card {...pkg} />
  <Card {...art} />
</div>

<p>
  <strong>
    Try editing this file (src/routes/index.svelte) to test live reloading.
  </strong>
</p>
