<script>
  let name = '';
</script>

<div>
  <h1>Hello {name}!</h1>
  <input bind:value={name}/>
</div>

<style>
  h1 {
    color: hotpink;
  }
</style>