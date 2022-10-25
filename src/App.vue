<template>
  <div class="container">
    <Heading/>
    <section id="content">
    <Title/>
    <Paragraph/>
    </section>
 
  </div>
</template>

<script>
import Heading from './components/heading.vue'
import Title from './components/title.vue';
import Paragraph from './components/paragraph.vue'
import { backgroundColorChange} from './assets/js/intersection.js'

export default {
  name: 'App',
  components: {
    Heading,
    Title,
    Paragraph
  }, 
  mounted(){
    backgroundColorChange(); 
  }
}


</script>
