<script>
    let props = $props();
</script>


<div class="element">{props.value}</div>

<style>
    .element {
        height: 5em;
        width: 5em;
        padding: .2em;


        border-radius: .5em;
        background-color: rgb(43, 43, 226);
    }
</style>