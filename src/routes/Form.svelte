<script>
	let value = '';
	let submitted = false;

	const handleSubmit = () => {
		submitted = true;
		console.log(value);
		setTimeout(() => {
			submitted = false;
			value = '';
		}, 1200);
	};
</script>

<main>
	<form on:submit|preventDefault={handleSubmit}>
		<label>
			what is computer music? <br />
			<input
				type="text"
				name="description"
				id="description"
				title="describe your tones here"
				maxlength="60"
				autocomplete="off"
				bind:value
			/>
			<button disabled={!value} type="submit">{submitted ? '~ty:)~' : 'submit'}</button>
		</label>
	</form>
</main>

<style>
	button {
		background-color: white;
		font-family: inherit;
		border: 1px solid black;
		color: inherit;
		margin: 0;
		cursor: pointer;
		padding: 4px;
	}

	button:disabled {
		opacity: 0%;
		cursor: none;
	}
	input[type='text'] {
		width: 33%;
		background: inherit;
		color: inherit;
		font-family: inherit;
		caret-color: blue;
		border: 1px solid black;
		border-radius: 0;
		padding: 3px;
	}

	input[type='text']:focus,
	button:hover,
	button:focus {
		outline: none;
		box-shadow: 3px 3px blue;
	}
</style>
