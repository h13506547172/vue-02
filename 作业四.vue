<template>
  <div>
    <input type="text" name="" id="" :value="iptdata" @input="fn">
  </div>
</template>

<script>
export default {
  data () {
    return {
      iptdata:''
    }
  },
  methods: {
    fn(e) {
      this.iptdata = e.target.value
    }
  }
}
</script>

<style>

</style>