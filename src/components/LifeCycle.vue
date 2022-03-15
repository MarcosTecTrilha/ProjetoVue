<template>
    <h1>Meu nome é: {{ nome }}</h1>
</template>

<script>
export default {
    name: 'LifeCycle',
    data() {
        return {
            nome: 'Ainda não sei'
        }
    }, 
    created() {
        setTimeout(() => {

        }, 1000);
        this.nome = "Marcos"
    },
    mounted() {
        
        this.nome = 'Pedro'
    }
}
</script>
