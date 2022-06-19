<template>
  <div>
    <div @click="onClick"><h1>PokerCard123</h1></div>
    {{ points + 'true' }}
  </div>
</template>
<script lang="ts">
import { PropType, defineComponent } from 'vue'
import { PokerCardType } from './pokerCard'

export default defineComponent({
  name: 'PokerCard',
  props: {
    pokerCard: {
      type: Object as PropType<PokerCardType>,
      required: true,
    },
  },
  methods: {
    onClick() {
      alert(`clicked`)
    },
  },
})
</script>

<style scoped></style>
