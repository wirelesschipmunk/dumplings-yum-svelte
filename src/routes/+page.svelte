<script>
	import BottomBar from "../lib/BottomBar.svelte";
	import FancyImg from "../lib/FancyImg.svelte";
	import TopBar from "../lib/TopBar.svelte";
</script>

<div>
	<TopBar />

	<div>
		<h1>Welcome To Dumplings Yum!!!</h1>
		<p>We make great chinese food and it's all organic.</p>
		<FancyImg src="src/images/img1.jpg" alt="orange chicken" />
	</div>

	<div>
		<h1>Since 2010</h1>
		<p>We've been serving top quality, delicious chinese food to everyone.(yay!)</p>
		<FancyImg src="src/images/img2.png" alt="noodles" />
	</div>

	<div>
		<h1>Check Out Our Menu</h1>
		<p>We have lots of delicious things to choose from</p>
		<button>Menu</button>
		<FancyImg src="src/images/img3.jpg" alt="veggies" />
	</div>

	<div>
		<h1>We do <span>takeout</span> to!</h1>
		<button>Order!</button>
		<FancyImg src="src/images/img4.png" alt="veggies" />
	</div>

	<BottomBar />
</div>

<style>
	:global(body) {
		font-family: "Telma", cursive;
		background-image: url(src/images/background-img.png);
		background-size: cover;
	}

	h1 {
		margin-top: 4.2em;
		margin-bottom: 0.5em;
		width: 550px;
		font-size: 60px;
		text-align: center;
	}

	p {
		font-size: 22px;
		text-align: center;
		width: 600px;
	}

	div {
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		align-items: center;
	}

	span {
		color: red;
	}
</style>
