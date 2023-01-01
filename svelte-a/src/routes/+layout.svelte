<script>
	import '@picocss/pico'
	import 'iconify-icon'
</script>

<button class="danger">
	<iconify-icon icon="lucide:home" style="color: purple;" width="23" height="20" />
	<span>Nav</span>
</button>

<slot />

<style>
	button {
		display: flex;
		background: linear-gradient(30deg, #49ba0b 0%, #ffcd1e 100%);
		color: black;
		align-items: center;
		justify-content: center;
		padding: 0.5rem 1rem;
		border-radius: 0.25rem;
		border: none;
		font-size: 0.85rem;
		font-weight: 500;
		cursor: pointer;
		max-width: 10%;
		gap: 0.2rem;
	}
</style>
