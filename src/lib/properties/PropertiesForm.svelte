<script>
  import PropertyLine from "./PropertyLine.svelte";

</script>

<div class="properties-container">
    <h1>Flexbox Properties</h1>
    <form action="">
        
        <PropertyLine text="display" options={[
            "flex",
            "inline-flex"
        ]}/>
        <PropertyLine text="flex-direction" options={[
            "row",
            "column",
            "row-reverse",
            "column-reverse"
        ]}/>

    </form>
</div>

<style>
    h1 {
        margin-bottom: .2em;
    }

    .properties-container {
        width: 70%;
        height: 100%;
    }

</style>