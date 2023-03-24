<script>
  import { card } from '../card-data'
</script>

<main>
<div class="card">
  <a href="{card.cardLink}">
  <figure>
    <h1>{card.name}</h1>
    <img src="{card.image}" width="300" height="380" alt="red">
    <figcaption>{card.description}</figcaption>
  </figure>
</a>
</div>  
</main>

<style> 
  main{
    flex: auto;
  }


</style>