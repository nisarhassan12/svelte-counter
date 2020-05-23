<script>
  let count = 0;
</script>

<h1>
	<span class={(count > 9 || count < -9) ? 'ml-4' : '' }>Count:</span>
	&nbsp;
	<span>{count}</span>
</h1>
<div>
  <button on:click={() => (count += 1)}>+1</button>
  <button on:click={() => (count -= 1)}>-1</button>
  <button on:click={() => (count = 0)}>Reset</button>
</div>
