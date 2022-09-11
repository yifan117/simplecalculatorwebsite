<script lang="ts">

import Buttons from './Buttons.svelte';
let value = "";

</script>

<div class="textfield">
    <div class="text">
        0
    </div>
</div>

<style>

.textfield {
    height: 70px;
    width: 228px;
    background-color: #000000;
    padding: 10px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}

.text {
    padding: 6px;
    color: #ffffff;
    display: flex;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 2.5em;
    justify-content: flex-end;
    align-items: center;
}
</style>