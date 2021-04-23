<script>
	export let emails;
</script>

<div class="container">
	{#each emails as email}
		<div class="row border">
			<div class="col c4">
				<p>{email.from}</p>
			</div>
			<div class="col c8">
				<p>{email.message}</p>
			</div>
		</div>
	{/each}
</div>

<style>
.row{
	text-align: center;
}
</style>
