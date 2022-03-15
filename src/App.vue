<template>
<div>
  <PrimeiroComponente/>
  <LifeCycle />
</div>  
</template>


<script>
   
  import PrimeiroComponente from "./components/PrimeiroComponente.vue"
  import LifeCycleVue from "./components/LifeCycle.vue"
import LifeCycle from "./components/LifeCycle.vue"

  export default {
    name: 'App',
    components: {
    PrimeiroComponente,
    LifeCycleVue,
    LifeCycle
}
  }
</script>