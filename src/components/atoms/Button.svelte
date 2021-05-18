<script>
    export let nativeType;
    export let type;
    export let disabled;
</script>
<button disabled={disabled} class={type}>
    <slot/>
</button>

<style>
    button {
        border-radius: 30px;
        padding: 17px 30px;
        cursor: pointer;
    }

    button.primary {
        background: hsl(176, 50%, 47%);
        color: white;
    }

    button.primary:hover {
        background: hsl(176, 72%, 28%);
    }

    button:disabled {
        background: hsl(0, 0%, 48%, 40%);
        pointer-events: none;
    }
</style>
