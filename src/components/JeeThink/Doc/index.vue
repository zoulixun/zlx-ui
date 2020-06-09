<template>
  <div>
    <svg-icon icon-class="link" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'zlxDoc',
  data() {
    return {
      url: 'http://zlx.vip/zlxDoc'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>