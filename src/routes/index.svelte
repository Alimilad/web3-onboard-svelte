<script>
	import { defaultEvmStores, connected, provider, chainId, chainData, signer, signerAddress, contracts } from 'svelte-ethers-store';

	import ConnectButton from '$lib/components/connectButton.svelte';
</script>

<main class="h-screen w-full flex flex-col justify-center gap-5">
	<ConnectButton />
</main>
