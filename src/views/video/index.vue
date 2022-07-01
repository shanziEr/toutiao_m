<template>
  <div class="video-container">
    <van-cell is-link @click="showPopup">展示弹出层</van-cell>
    <van-popup v-model="show" position="left" :style="{ width: '80%',height:'100%' }"  closeable round
  close-icon="close">内容  </van-popup>
  </div>
</template>

		<script>
export default {
  name: "VideoPage",
  components: {},
  props: {},
  data() {
    return {
      show: false,
    };
  },
  computed: {},
  watch: {},
  created() {},
  mounted() {},
  methods: {
    showPopup() {
      this.show = true;
    },
  },
};
</script>

		<style scoped></style>