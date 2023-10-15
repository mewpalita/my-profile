<script>
import CommentSection from '@/components/commentSection.vue'

export default {
  components: {
    CommentSection
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
  <div>
    <div class="header">
      <img src="https://w7.pngwing.com/pngs/672/585/png-transparent-rukia-kuchiki-byakuya-kuchiki-ichigo-kurosaki-orihime-inoue-renji-abarai-ichigo-kurosaki-black-hair-human-fictional-character.png" alt="" width="150" height="150">
      <h1>Kuchiki</h1>
      <h1>Rukia</h1>
      <div class="line"></div>
      <p>DESIGNER/WRITER</p>
    </div>

    <div class="content">
      <img src="https://cdn.pixabay.com/photo/2023/10/03/09/19/sunrise-8290940_1280.jpg" alt="" width="500" height="300">
      <div class="b" style="color: gray;">
        <p> 9 years ago</p>
        <h1>Sample photo post with <br>unpopular long title <br>and no read more link</h1>
        <h3>Suspendisse tempor magna vitae mollis tincidunt. <br>Integer sapien fringilla mauris.</h3>
        <h4>Donec nulla elit, dignissim et malesuada a, posuere sit amet nisl. <br>Sed id mi eu magna commodo pharetra consequat ac neque. In ac <br>enim at nisi molestie mattis sed a ante. Sed condimentum augue <br>at risus commodo iaculis. Fusce nulla orci.</h4>
        
        <p>#photo &nbsp;&nbsp; #unsplash</p>
        <div class="icons">
          <span class="material-symbols-outlined">open_in_new</span>
          <a href="#"><span class="material-symbols-outlined">favorite</span></a>
        </div>
      </div>
      
    </div>
    
    
    <div class="header">
      <CommentSection />
    </div>

  </div>
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