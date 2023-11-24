<template>
  <div>
    <p>{{ text }}</p>
    <button @click="onClickButton">ボタン</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: "this is page1",
    };
  },
  methods:{
    onClickButton(){
      alert(this.text)
    }
  },
  mounted(){
    alert('マウントされました')
  }
};
</script>
<style lang="scss" scoped>
p {
  color: teal;
}
</style>
            