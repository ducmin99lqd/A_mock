<template>
    <div>
        Helloo duc buiiii anh em oi
        {{product}}
        
    </div>
</template>

<script>
    export default {
        computed:{
            product(){
                return this.$store.getters.getProductById(this.$route.params.id)
            }
        }
    }
</script>
