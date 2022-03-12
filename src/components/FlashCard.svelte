<script>
	export let question = 'Well Done!';
	export let side = 'front';
</script>

<div class="card">
	<p class="side">{side}</p>
	<p class="question">{question}</p>
</div>

<style>
	.card {
		background-color: rgb(207, 232, 220);
		width: 400px;
		height: 200px;
		position: absolute;
		top: 50%;
		left: 50%;
	}

	.side {
		font-style: italic;
		text-align: end;
		padding-right: 1em;
	}

	.question {
		text-align: center;
		font-family: 'Courier New', Courier, monospace;
		font-size: x-large;
		font-weight: bold;
	}
</style>
