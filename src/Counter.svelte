<script>
  let counter = 0;  // counter variable
  const handleClick = () => { //Function to add 1 to our variable
    counter += 1;
  };
</script>
<style>
  button{
    border:0px;
    background: #3380ef;
    color:white;
  }
</style>
<div class=”counterComponent”>
  <button on:click={handleClick}>plus 1</button>
  <section>My couter is: {counter}</section>
</div>