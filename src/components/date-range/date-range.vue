<template>
  <cube-date-picker
    :min="min"
    :max="max"
    v-model="start"></cube-date-picker>
  <cube-date-picker></cube-date-picker>
</template>

<script>
const COMPONENT_NAME = 'cube-date-range'
export default {
  name: COMPONENT_NAME,
  props: {
    min: {
      type: Array,
      default() {
        return []
      }
    },
    max: {
      type: Array,
      default() {
        return []
      }
    },
    start: {
      type: Array,
      default() {
        return []
      }
    },
    end: {
      type: Array,
      default() {
        return []
      }
    }
  }
}
</script>
