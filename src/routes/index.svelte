<script>
	import Search from '$lib/Search/index.svelte';
	import Email from '$lib/Email/index.svelte';
    let user_input;

	let emails = [
		{ from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
        { from: 'James Van Niekerk', message: 'test email innards' },
		{ from: 'Gabri Botha', message: 'test email innards and more' },
	];
</script>

<Search>
    <input class="smooth full-width" bind:value={user_input}>
</Search>

<Email emails={emails} />