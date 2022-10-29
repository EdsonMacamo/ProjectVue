<template>
    <h1>Meu nome e: {{nome}}</h1>
</template>

<script>
export default{
    name:"Lifecycle",
    data() {
        return{
            nome:"aind nao sei"
        }
    },
    created(){
        setTimeout(() =>{
            this.nome = "Edson"
    }, 1000);
        
    },
    mounted(){
        setTimeout(() => {
            this.nome = "pedro"
        }, 2000)
        
    }

}
</script>