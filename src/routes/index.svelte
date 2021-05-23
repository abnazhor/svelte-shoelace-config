<script>
	import { onMount } from 'svelte';
    import "@shoelace-style/shoelace/dist/themes/base.css";

	onMount(async () => {
		await import('@shoelace-style/shoelace/dist/components/button/button');
	});
</script>

<sl-button>Test</sl-button>