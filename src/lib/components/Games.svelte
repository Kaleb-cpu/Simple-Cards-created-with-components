<script>
  import { games } from '../games-data'
</script>

<main class="cards">
<div class="card">
  <a href="{games[0].gameLink}">
    <figure>
      <h1>{games[0].gameName}</h1>
      <img src="{games[0].gameImage}" width="200" height="280" alt="red">
      <figcaption>{games[0].gameDescription}</figcaption>
    </figure>
  </a>
</div>  

<div class="card">
  <a href="{games[1].gameLink}">
    <figure>
      <h1>{games[1].gameName}</h1>
      <img src="{games[1].gameImage}" width="200" height="280" alt="red">
      <figcaption>{games[1].gameDescription}</figcaption>
    </figure>
  </a>
</div>  
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