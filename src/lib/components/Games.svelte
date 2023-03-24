<script>
  import { games } from '../games-data'
</script>

<main class="cards">

{#each games as game}
  <div class="card">
    <a href="{game.gameLink}">
      <figure>
        <h1>{game.gameName}</h1>
        <img src="{game.gameImage}" width="200" height="280" alt="red">
        <figcaption>{game.gameDescription}</figcaption>
      </figure>
    </a>
  </div>  
{/each}
</main>

<style> 
  .cards {
    display: flex;
    flex: auto;
  }



  .card {
    border: 5px solid darkcyan;
    width: max-content;
    margin: auto;
    border-radius: 1em;
    text-align: center;
  }
  .card:hover {
    background-color: beige;

  }
  
  .card a{
    text-decoration: none;
    color: black;
  }
  
  figcaption{
    width: 30ch;
    font-size: 1.2rem;
  }
</style>