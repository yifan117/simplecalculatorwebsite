<script lang="ts">

    import Calculator from "svelte-material-icons/Calculator.svelte";
    import Calcvar from "svelte-material-icons/CalculatorVariant.svelte";
    import Heading from "../cooltext418321535295329.png";
    import Heading2 from "../cooltext418321742562341.png";

</script>

<div class="header">

    <Calculator size="70px"/>
    <img src={Heading2} alt = "Yifan's Simple Calculator"/>
    <Calcvar size="70px"/>
</div>

<style>

.header {

    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #A9A9A9;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

}

</style>