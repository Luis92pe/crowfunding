<script>
    export let value;
</script>

<div class="Progress-container">
    <div class="progress-bar" style={`width:${value}%`}></div>
</div>

<style>
    .Progress-container {
        height:15px;
        border-radius:100px;
        background-color: #EDEDED;
    }
    .progress-bar {
        height:100%;
        border-radius:100px;
        background-color: hsl(176, 72%, 28%);
    }
</style>
