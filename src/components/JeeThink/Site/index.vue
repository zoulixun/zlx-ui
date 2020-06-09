<template>
  <div>
    <svg-icon icon-class="guide" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'zlxSite',
  data() {
    return {
      url: 'http://zlx.vip'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>