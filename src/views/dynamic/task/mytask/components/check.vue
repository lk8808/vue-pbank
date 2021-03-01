<template>
  <div>
    处理
  </div>
</template>

<script>

  export default {
    props: {
      task: {
        required: true,
        type: Object
      }
    },
    watch: {
      task(val) {
        console.log(val)
      }
    },
    created() {
    },
    methods: {
      init() {

      },
      save() {

      }
    }
  }
</script>
