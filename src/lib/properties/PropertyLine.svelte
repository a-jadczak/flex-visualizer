<script>
    let props = $props();
    let options = $state(props.options)
</script>


<div class="property-line">
    <label for="select-{props.text}">
        <span>{props.text}:</span>
        <select name="select-{props.text}">
            {#each options as option}
                <option value={option}>{option}</option>
            {/each}
        </select>
    </label>
</div>


<style>
    * {
        font-size: 1.1rem;
    }
    .property-line {
        margin-bottom: .5em;
    }
    label {
        display: flex;
        justify-content: space-between;

        width: 100%;
    }
    select {
        width: 40%;

        border-radius: .5em;
        padding: .2em;
        outline: none;
        border: none;

        background-color: var(--carolina-blue);
    }
    option {
        background-color: var(--carolina-blue);
    }
    
</style>