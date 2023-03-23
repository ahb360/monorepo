<template>
  <div class="about">
    <base-button></base-button>
    <br>
    <base-input></base-input>
  </div>
</template>

<script lang="ts">
import {defineComponent} from 'vue'
import {BaseButton, BaseInput} from "base-components"

export default defineComponent({
  components: {
    BaseButton,
    BaseInput
  }
})
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
