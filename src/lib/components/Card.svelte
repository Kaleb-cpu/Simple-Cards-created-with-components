<script>
  import { card } from '../card-data'
</script>

<main>
<div class="class">
  <a href="{card.cardLink}">
    <figure>
      <h1>{card.name}</h1>
      <img src="{card.image}" width="200" height="280" alt="red">
      <figcaption>{card.description}</figcaption>
    </figure>
  </a>
</div>  
</main>

<style> 
  main {
    flex: auto;
  }
  .class {
    border: 5px solid darkcyan;
    width: max-content;
    margin: auto;
    border-radius: 1em;
    text-align: center;
  }
  .class:hover {
    background-color: beige;

  }
  
  .class a{
    text-decoration: none;
    color: black;
  }
  
  figcaption{
    width: 30ch;
    font-size: 1.2rem;
  }
</style>