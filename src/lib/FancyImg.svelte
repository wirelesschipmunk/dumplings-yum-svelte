<script>
	export let src;
	export let alt;
</script>

<img {src} {alt} />

<style>
	img {
		width: 450px;
		box-shadow: 1px 1px 15px;
		border-radius: 30px;
		transition: all 0.5s;
		cursor: pointer;
		margin-bottom: 2em;
	}

	img:hover {
		width: 500px;
		transform: rotate(5deg);
	}

	img:active {
		width: 480px;
		transform: rotate(2deg);
	}
</style>
