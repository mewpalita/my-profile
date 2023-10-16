<script>
import CommentSection from '@/components/commentSection.vue'
import { RouterView } from 'vue-router';

export default {
  components: {
    CommentSection,
    RouterView
},
  name: 'App',
  data () {
    return {
     avatar: '' 
    }
  }
}
</script>

<template>
  <RouterView />
</template>


<style>
.header {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center; 
  margin-top: 10%;
}
h1{
  margin-block: 0;
  font-size: 3em;
}
h3{
  font-size: 1.4em;
}
h4{
  font-size: 1.07em;
}
.line{
  height: 3px; width: 200px;
  background-color: black;
  margin: 23px;
}
.content{
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: left;
}
.b{
  background-color: bisque;
  width: 550px;

}

</style>