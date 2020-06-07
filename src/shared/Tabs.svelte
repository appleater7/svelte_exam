<script>
    export let items;
    export let activeItem;

</script>
<!-- 20강 작업중 -->
<div class="tabs">
    <ul>
       {#each items as item} 
            <li>
                <div>{item}</div>
            </li>
       {/each}
    </ul>
</div>

<style></style>