<template>

<section id="projects"> 
<h3> PROJECTS</h3> 
    <v-container fluid class="white">
      <v-row
      dense>
        <v-col cols="4">
          <v-img src="../assets/IMG1.png"></v-img>
        </v-col>
        <v-col cols="4">
          <v-img src="../assets/IMG2.png"></v-img>
        </v-col>
        <v-col  cols="4">
          <v-img src="../assets/Poster.png"></v-img>
        </v-col>
      </v-row>
      <v-row>
        <h1>Graphic posters </h1>
        <h2 class="grey--text">That I made for presentations my projects. 
          I used the programme Rhinoceros for the first and last one.
          Leknín was projected about creating yoga/meditation space on the lake. 
          The Connection was a project where I created student shared space in Scandinavia.</h2>
      </v-row>
       <v-row
      dense>
        <v-col cols="4">
          <v-img src="../assets/IMG3.png"></v-img>
        </v-col>
        <v-col cols="4">
          <v-img src="../assets/IMG4.png"></v-img>
        </v-col>
        <v-col cols="4">
          <v-img src="../assets/IMG5.png"></v-img>
        </v-col>
      </v-row>
      <v-row>
        <h1>Tattoo sketches </h1>
        <h2 class="grey--text">My tattoo sketches that I created with Procreate with clients requests 
          how it should look I created these designs.</h2>
      </v-row>
      <v-row
      dense>
        <v-col cols="12">
          <v-img src="../assets/IMG6.png"></v-img>
        </v-col>
      </v-row>
      <v-row>
        <h1>Web site layout </h1>
        <h2 class="grey--text">
        During my study at Business Academy SouthWest I gained knowledge
        how to create in Adobe XD layout for Website.
        This is the layout of our first exam project from 1st semester about space.</h2>
      </v-row>
      <v-row
      dense>
        <v-col cols="6">
          <v-img src="../assets/IMG7.png"></v-img>
        </v-col>
        <v-col cols="6">
          <v-img src="../assets/IMG8.png"></v-img>
        </v-col>
      </v-row>
      <v-row>
        <h1> Design </h1>
        <h2 class="grey--text">
       
        In Illustrator I created the design of objects for a web site. 
        First one is from our first exam project about space.
        The second one is my mini-me. </h2>
      </v-row>
    </v-container>

  </section>
</template>

<script>
    export default {
        name: 'Projects',
        data: () => ({

    }),
    }
</script>

<style lang="scss" scoped>
#projects {
    padding-top: 3%;
    margin-left: 25%;
    margin-right: 5%;
}
h1 {
  font-size: 100%;
  display:flex;
  padding-top: 2%;
  padding-bottom: 2%;
}
h2 {
  font-size: 90%;
  padding-bottom: 12%;
}
h3 {
  font-size: 300%;
  padding-top: 5%;
  padding-bottom: 5%;
}

</style>