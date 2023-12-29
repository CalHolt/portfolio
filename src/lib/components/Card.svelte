<script>
  export let cardTitle;
  export let item1;
  export let item2;
  export let item3; 
</script>
<div class="card">
  <h1 class="text-xl">{cardTitle}</h1>
  <ul>
    <li>{item1}</li>
    <li>{item2}</li>
    <li>{item3}</li>
  </ul>
</div>
<style>
  h1 {
    font-family: 'Fugaz One', sans-serif;
    margin-bottom: 10px;
    text-decoration: underline;
  }
  li {
    font-family: 'work sans';
  }
  .card {
    padding: 2rem;
    box-shadow: 10px 10px #000000;
    border: 2px solid #000000;
  }
</style>
