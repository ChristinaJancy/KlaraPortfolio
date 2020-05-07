<template>
  <section id="main">
    <div id="header">
   
      <h1 class="headerText">KLARA NEMCIKOVA</h1> 
      <div class="grey--text">
      <h3 class="headerText"> ESBJERG, DENMARK - +45 51 70 39 75 - KLARANEMCIKOVA99@GMAIL.COM</h3>
      </div>
      <p class="headerText">Ahoj! My name is Klara Nemcikova and currently I’m studying at Business Academy SouthWest in Denmark. I have chose multimedia design programme. I also studied interior design in high school in Czech Republic which I am from. As a person I’m really productive, which means I can’t stop with assigned work. I’m also pretty perfectionist. Every time I try my best to put my work further and work on the details. Which means I’m creative mind and I can focus on increase of the work. I have really quick adaptation so new environment for me isn’t a problem. Responsibility is also one of my strong value and you can always rely on me. Im always up for changes and challenges. My biggest passion is definitely art and design. Therefor I want to work as a graphic designer or Illustrator, because I also have the ability of drawing.</p> 
    </div>

    <div id="video">
      <video width="70%" height="auto" controls>
        <source src="../assets/Klara_Nemcikova.mp4" type="video/mp4">
      </video>
    </div>

   
    <v-row
      dense>
        <v-col cols="6">
          <v-img src="../assets/CV2.png"></v-img>
        </v-col>
        <v-col cols="6">
          <v-img src="../assets/CV.png"></v-img>
        </v-col>
      </v-row>


  </section>
</template>

<script>
export default {
  name: 'Main', 
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h1 {
    font-size: 300%;
    
    }

#main {
  
  margin-top: 10%;
  margin-left: 25%;
  margin-right: 5%;
}

.headerText {
  padding-bottom: 0.25em;
  
}

</style>


