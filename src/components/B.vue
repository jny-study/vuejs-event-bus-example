<template>
    <div v-if="drawer">
        이제 나를 볼 수 있어요
    </div>
    <div v-else>
        이제는 안보입니다
    </div>
</template>

<script>
  export default {
    data() {
      return {
        drawer: true,
      };
    },
    created() {
      this.$EventBus.$on('click-icon', () => {
        this.drawer = !this.drawer;
      });
    },
  };
</script>
