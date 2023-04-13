<script lang='ts'>
import '../theme.postcss';
import '@skeletonlabs/skeleton/styles/all.css';
import '../app.postcss';
import { AppShell,LightSwitch } from '@skeletonlabs/skeleton';
import 'iconify-icon';

</script>

<AppShell>

	<svelte:fragment slot="sidebarLeft">
		<div class="grid grid-cols-1 m-4 py-4 gap-y-8"> 
		
			<LightSwitch> </LightSwitch>

				<a href="/peenuts">
				<button type="button" class="btn-icon variant-filled"> <iconify-icon icon="game-icons:peanut"></iconify-icon></button></a>

				<a href="/banana">
				<button type="button" class="btn-icon variant-filled"> <iconify-icon icon="icon-park-outline:banana"></iconify-icon></button></a>

				<a href="/jam">
				<button type="button" class="btn-icon variant-filled"> <iconify-icon icon="game-icons:berries-bowl"></iconify-icon></button></a>

				<a href="/">
				<button type="button" class="btn-icon variant-filled"> <iconify-icon icon="material-symbols:home"></iconify-icon></a>
					
			</div>
	</svelte:fragment> 


<slot />

</AppShell>
