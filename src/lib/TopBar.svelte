<div>
	<span>Dumplings Yum!</span>
	<p />
	<button>Home &#9751;</button>
	<button>Menu &#10070;</button>
	<button>Order &#9832;</button>
	<button>Contact &#9742;</button>

	<button>About &#9787;</button>
</div>

<style>
	div {
		text-align: center;
		font-size: 25px;
		top: 0;
		left: 0;
		width: 100%;
		padding: 0.1em;
		box-shadow: 1px 1px 15px;
		border-radius: 10px;
		position: fixed;
		background-color: rgba(0, 0, 0, 0.6);
		backdrop-filter: blur(3px);
		z-index: 5;
	}

	span {
		font-family: "Pencerio", cursive;
		background-color: rgba(0, 0, 0, 0.3);
		box-shadow: 1px 1px 15px black;
		/* background: linear-gradient(15deg, rgb(92, 63, 255), rgb(222, 0, 0)); */
		font-weight: bold;
		font-size: 65px;
		color: rgb(255, 235, 219);
		text-shadow: 1px 1px 3px;
		padding: 0.3em 0.4em;
		border-radius: 20px;
	}

	:global(button) {
		font: inherit;
		background: linear-gradient(45deg, rgb(255, 63, 63), rgb(222, 0, 0));
		border-radius: 8px;
		margin-bottom: 1em;
		border-style: solid;
		border-color: black;
		box-shadow: 1px 1px 15px;
		width: 5.8em;
		height: 1.8em;
		cursor: pointer;
		transition: all 0.5s;
	}

	:global(button):hover {
		transform: rotate(3deg);
		opacity: 0.8;
	}

	:global(button):active {
		transform: rotate(2deg);
		opacity: 0.5;
	}
</style>
