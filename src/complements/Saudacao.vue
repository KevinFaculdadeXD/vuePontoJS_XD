<template>
    <div>
        <h2>Seja bem vindo {{ nome }}</h2>
    </div>
</template>

<script>
    export default{
    props: {
    nome: String
    }
</script>