

<template>

 <div>

  <h1>Welcome</h1>

 <img  width="150px" alt="Vue" src="../../src/images/vue.png">

 <br />

 <!--Test--->
 <!--<span class="test">Hey dude...</span>-->

 <h2>Webpack 5 configured from scratch to serve Vue.js</h2>
   <react-button text="buttonText" />
 </div>

</template>

<script>
import ReactButton from './../ReactButton';
export default {
    name: 'AppHome',
    components: { ReactButton },
};


</script>


<style scoped>

    h2  {
        color: #404040;
    }

</style>

