<template lang="pug">
    div
        h1 Este es un componente hijo
        componente-local
</template>

<script>
  import ComponenteLocal from './ComponenteLocal.vue'
export default {
    components: {
        ComponenteLocal
    }
    
}
</script>