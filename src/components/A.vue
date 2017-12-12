<template>
  <button v-on:click="$EventBus.$emit('click-icon')">
    button
  </button>
</template>
