<template>
  <h2>Counter</h2>
  <hr/>
  <h3>{{msg}}</h3>
</template>

<script>
export default {
name: "PruebaComponent",
props:{msg:String},
methods:{
    getValue(){return this.msg;}
},
computed:{
    getValueFinal(){return this.msg + 1;}
}
}
</script>

<style>

</style>