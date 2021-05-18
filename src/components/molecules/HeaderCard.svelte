<script>
	import Card from "../atoms/Card.svelte";
	import Button from "../atoms/Button.svelte";
</script>

<Card>
    <h1>Mastercraft Bambo Monitor Riser</h1>
    <p>A beautiful & handcrafted monitor stand to reduce neck and eye strain. </p>
    <div class="buttons-container">
        <Button type="primary">Back this projects</Button>
        <Button>C</Button>
    </div>
</Card>

<style>
    .buttons-container {
        display: flex;
        justify-content: space-between;
    }
</style>
