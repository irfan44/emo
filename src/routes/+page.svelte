<script>
	import { Alert } from 'flowbite-svelte';

	async function hello() {
		// @ts-ignore
		console.log(await window.electronAPI.getAccessToken());
	}

	hello();
</script>

<div class="p-8">
	<Alert>
		<span class="font-bold">Info alert!</span> Change a few things up and try submitting again.
	</Alert>
</div>
