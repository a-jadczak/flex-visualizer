<script>
  import DisplayBox from "./lib/DisplayBox.svelte";
  import PropertiesForm from "./lib/properties/PropertiesForm.svelte";
</script>

<main>
  <PropertiesForm/>
  <DisplayBox/>
</main>

<style>
    main {
        display: flex;
        justify-content: center;
        gap: 2em;

        width: 70vw;
        height: 60vh;
        
        padding: 2em;
        border: 2px solid var(--midnight-green);
    }
</style>
