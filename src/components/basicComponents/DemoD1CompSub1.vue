<!--declares a demo component, No. is DemoD1

-->
<template>
  <div id="DemoD1CompSub1">
    <span>
      <h5>{{ id }}:{{ title }}</h5>
    </span>
  </div>
</template>

<script>
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'DemoD1CompSub1',
  props: ['title', 'id']
})
</script>
//
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a,
span {
  color: red;
}
</style>
