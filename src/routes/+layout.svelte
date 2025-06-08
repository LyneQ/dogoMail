<script lang="ts">
	import { enhance } from '$app/forms';

	let { data, children } = $props();
</script>

<div>
	<main>
		{@render children()}
	</main>
</div>
