<template>
    <div>
        <p @click="handleClick">
            Meu parágrafo é: {{ paragraph }}</p>
    </div>
</template>

<script>   
    export default {
        props: ['paragraph'],
        methods: {
            handleClick() {
                console.log("Alguem clicou no parágrafo");
            }
        }
    }
</script>
<style>
p {
    background-color: lightblue;
    font-weight: 200;
    cursor: pointer;
}
</style>

<style>
    m{
        background-color: purple;
        color: white;
        position: relative;
        top: 20px;
    }
</style>
