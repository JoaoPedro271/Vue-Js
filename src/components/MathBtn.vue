<template>

    <div>
        <p @click="numClick">
            O número escondido é: {{ valor }}
        </p>
    </div>

</template>

<script>
    export default {
        props: ['valor'],
        methods: {
            numClick(){
                console.log("Clicaram em mim!");
            }
        }
    }
</script>