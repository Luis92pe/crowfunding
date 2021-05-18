<script>
	import Card from "../atoms/Card.svelte";
	import Progress from "../atoms/Progress.svelte";
</script>

<Card>
    <div class="Counters-container">
        <div>
            <h2>$43.234</h2>
            <small>of $100.000</small>
        </div>
        <div>
            <h2>$43.234</h2>
            <small>of $100.000</small>
        </div>
        <div>
            <h2>$43.234</h2>
            <small>of $100.000</small>
        </div>
    </div>
    <Progress value={65} />
</Card>

<style>
    .Counters-container {
        display: flex;
        justify-content: space-between;
        flex-direction: column;
    }
</style>
