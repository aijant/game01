<template>
  <div class="monsterSlayer">    
    <MonsterSlayer />
  </div>
</template>

<script>
// @ is an alias to /src
import MonsterSlayer from '@/components/MonsterSlayer.vue'

export default {
  name: 'home',
  components: {
   MonsterSlayer
  }
}
</script>
