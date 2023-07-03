<template>
  <div class="box">
    <div class="cbox">
      <ul>
        <li v-for="(item, index) in tabs" :key="index">{{ item.name }}---{{ item.age }}</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tabs: [
        { name: "张思思", age: "9" },
        { name: "王九九", age: "19" },
        { name: "梦碎碎", age: "29" },
        { name: "李牛牛", age: "39" }
      ]
    }
  },
  methods: {},
  created() {},

  mounted() {},
  components: {},
  computed: {},
  watch: {}
}
</script>

<style lang="scss" scoped>
.box {
  width: 100%;
  height: 100%;
  .cbox {
    width: 50%;
    height: 50%;
    margin: 50px auto;
    background-color: pink;
  }
}
</style>
