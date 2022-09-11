<script lang="ts">

    import Buttons from '../lib/components/Buttons.svelte';
    import Header from '../lib/components/Header.svelte';
    
</script>

<title>Yifan's Simple Calculator</title>

<div class="page">

    <div class="headercenter">
        <div class="header">
            <Header/>
        </div>
    </div>
    
    <div class="calccomplete">
        <Buttons/>
    </div>
</div>

<style>

.page {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100vh;
    width: 100vw;
}
.calccomplete {
    width: 100vw;
    height: 100vh;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
}

.headercenter {
    display: flex;
    justify-content: center;
}

.header {
    padding: 10px;
    width: 80%;
    margin: 20px;
    border-radius: 8px;
    background-color: #A9A9A9;
    display: flex;
    justify-content: center;
}

</style>