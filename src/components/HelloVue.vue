<template>
  <div class="hello">
    {{name}}

  </div>
</template>

<script>
export default {
    name:"HelloVue",
    data(){
        return {
            name:"홍길동"
        }
    }
}
</script>

<style>
    div{
        height: 100px;
        width: 500px;
        background-color: gray;
    }
    .hello{
        background-color: green;
    }
</style>