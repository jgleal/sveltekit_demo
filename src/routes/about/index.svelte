<script>
	import { count } from '$stores/count'
</script>
<style>
    #counter {
        margin-top: 1em;
    }
    input[type="number"] {
        -moz-appearance: textfield;
        width: 2em;
        color: #f5c262;
        text-align: center;
    }
    input[type="number"]::-webkit-inner-spin-button, 
    input[type="number"]::-webkit-outer-spin-button { 
        -webkit-appearance: none; 
        margin: 0; 
    }
    label, input {
        font-size: 3rem;
    }
</style>
<div id="counter">
    <label for="counter">Counter:</label>
    <input id="counter" type="number" bind:value={$count}>
</div>
<p>Visit the <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte apps.</p>


