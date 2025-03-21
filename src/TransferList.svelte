<script>
    import {onMount} from "svelte";
    let leftList = [];
    let rightList = [];

    onMount(async () => {
        const response = await fetch("http://localhost:8000/api/get_names/");
        const data = await response.json();
        leftList = data;
    });

    const moveToRight = (item) => {
        leftList = leftList.filter((name) => name.id !== item.id);
        rightList = [...rightList, item];

    };

    const moveToLeft = (item) => {
        rightList = rightList.filter((name) => name.id !== item.id);
        leftList = [...leftList, item];
    };
</script>

<style>
    .transfer-list {

    }
    .list-box {

    }
    .button {

    }
</style>

<div class="transfer-list">
    <div class = "list-box">
        <h1>Available Names</h1>
        <ul>
            {#each leftList as name}
                <li>
                    {name.name}
                    <button class="button" on:click={() => moveToRight(name)}> move </button>
                </li>
            {/each}
        </ul>
    </div>

    <div class = "list-box">
        <h1>Selected Names</h1>
        <ul>
            {#each rightList as name}
                <li>
                    {name.name}
                    <button class="button" on:click={() => moveToLeft(name)}> move </button>
                </li>
            {/each}
        </ul>
    </div>
</div>