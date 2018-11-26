<template>
 <a class="tags-view-item" @click="cl">close</a>  
</template>

<script>
export default {
  name: "quanbuguanbi",
  components: {},
  methods: {
      cl(ev){
          this.$emit('click',ev)
      }
  }
};
</script>




<style>
</style>

