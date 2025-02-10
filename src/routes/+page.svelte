<script lang="ts">
	import '../app.css';
	import { AreaChart } from 'layerchart';
	import { data } from './data';
</script>

<main class="p-10">
	<p class="text-2xl">Hello world</p>

	<div class="h-[300px] p-4 border rounded">
		<AreaChart {data} x="date" y="value" />
	</div>
</main>
