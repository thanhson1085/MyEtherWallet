<template>
  <div class="crypto-icons">
    <img :src="eth" />
  </div>
</template>

<script>
import eth from '@/assets/images/networks/circle/eth.svg';

export default {
  components: {},
  props: {
    crypto: {
      type: String,
      default: ''
    }
  },
  data() {
    return {
      eth: eth
    };
  },
  mounted() {},
  methods: {}
};
</script>

<style lang="scss" scoped>
@import 'CryptoIcons.scss';
</style>
