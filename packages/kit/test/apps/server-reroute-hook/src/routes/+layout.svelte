<script>
	import { setup } from '../../../../setup.js';

	setup();

	const { children } = $props();
</script>

<a href="/">/</a>
<a href="/reroute">/reroute</a>
<a href="/test">/test</a>
<a href="/somewhere">/somewhere</a>
<a href="/not-rerouted">/not-rerouted</a>

{@render children()}
