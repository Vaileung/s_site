<template>
  <div id="online-chat" class="fixed">
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Contact',
  data() {
    return {
      infoList: [
        {
          icon: 'phone-outline',
          text: '150 0203 2816'
        },
        {
          icon: 'message',
          text: 'chreta.com@gmail.com'
        },
        {
          icon: 'map-location',
          text: '广州市白云区天健广场302'
        }
      ]
    }
  },
  components: {
    FlexBox
  }
}
</script>

<style scoped>
.fixed {
  position: fixed;
}
</style>
