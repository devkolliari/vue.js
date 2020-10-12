<template>
  <div>
    <Counter 
      :year="2020"
      :month="12"
      :date="25"
      :hour="23"
      :minute="59"
      :second="59"
      :millisecond="31"
    />
  </div>
</template>

<script>
import Counter from '@/components/Counter.vue'
  export default {
    components: {
      Counter
    }
  }
</script>

<style lang="scss" scoped>
</style>