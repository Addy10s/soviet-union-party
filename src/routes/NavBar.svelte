<script lang="ts">
import { resolve } from '$app/paths';
</script>
<nav
	id="global-navbar"
	class="my-8 group bg-red-600 text-yellow-400 *:text-shadow-ctp-base z-100 mx-auto table content-center space-x-0 rounded-xl px-2 py-1 text-center text-[4vw] shadow-2xl *:rounded-md *:px-3 *:py-1 *:align-middle lg:rounded-[3rem] lg:text-[3rem]"
>
	<a
		href={resolve("/")}
		class="group text-ctp-text align-middle text-[4vw] font-black lg:text-[5rem]"
	>
		<b>☭ The Fall of the Soviet Union ☭</b></a
	>
	<br />

	<a
		href={resolve("/Geography")}
		class=" text-nowrap opacity-100 transition-opacity duration-300 ease-out pointer-fine:lg:opacity-85 pointer-fine:lg:group-hover:opacity-100"
		><b> Geography </b></a
	>

	<a
		href={resolve("/Culture")}
		class="transition-opacity duration-300 ease-out group-hover:opacity-100 pointer-fine:lg:opacity-85"
		><b> Culture </b></a
	>
	<a
		href={resolve("/Economics")}
		class="transition-opacity duration-300 ease-out group-hover:opacity-100 pointer-fine:lg:opacity-85"
		><b> Economics </b></a
	>
	<a
		href={resolve("/PolSys")}
		class="transition-opacity duration-300 ease-out group-hover:opacity-100 pointer-fine:lg:opacity-85"
		><b> Political Systems </b></a
	>
    <a
		href={resolve("/Hist")}
		class="transition-opacity duration-300 ease-out group-hover:opacity-100 pointer-fine:lg:opacity-85"
		><b> History </b></a
    >
	<a
		href={resolve("/Connections")}
		class="transition-opacity duration-300 ease-out group-hover:opacity-100 pointer-fine:lg:opacity-85"
		><b> Connections </b></a
    >
</nav>