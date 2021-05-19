<template>
<appHeader/>
<home/>
</template>


<script>
//import HelloWorld from './components/HelloWorld.vue'
import home from './components/home.vue'
import appHeader from './components/appHeader.vue'

export default{
 components:{home,appHeader},
};

</script>