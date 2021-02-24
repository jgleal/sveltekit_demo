<script>
	import { count } from '$stores/count'
</script>

<button on:click={count.decrement}>-</button>
<span>Cunter: {$count}</span>
<button on:click={count.increment}>+</button>

<style>
	button {
		font-family: inherit;
		font-size: inherit;
		padding: 1em;
		color: #ff3e00;
		background-color: rgba(255, 62, 0, 0.1);
		border-radius: 2em;
		border: 2px solid rgba(255, 62, 0, 0);
		outline: none;
		width: 4em;
	}
	span {
		padding: 2em;
	}
	button:hover {
		border: 2px solid #ff3e00;
	}
	button:active {
		background-color: rgba(255, 62, 0, 0.2);
	}
</style>