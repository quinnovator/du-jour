<script lang="ts">
	import boards from './boards.svg';
	export let smallMode: boolean = false;
</script>

<div class="{smallMode? "h-12" : "h-16"} flex">
	<img class="h-full" src={boards} alt="Project Room" />
	<h1 class="font-mono {smallMode? "text-sm" : "text-lg"} my-auto">DU<br />JOUR</h1>
</div>
