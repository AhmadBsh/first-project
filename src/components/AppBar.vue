  <template>
  <div>

    <v-app-bar
      color="deep-purple accent-4"
      dense
      dark
      fixed
    >
    
      <v-app-bar-nav-icon @click="drawer = true">
      </v-app-bar-nav-icon>

      <v-toolbar-title style="color:aqua">T-P-T</v-toolbar-title>

    <v-btn icon>
        <v-icon style="color:yellow">mdi-lightbulb-on</v-icon>
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn rounded text>Home</v-btn>
      <v-btn rounded text>About </v-btn>
      <v-btn rounded text>Programming Websites</v-btn>
      <v-btn rounded text>Hosting Services </v-btn>
      <v-btn   rounded text>Cloud Storage</v-btn>
      <v-btn  rounded text>Servers </v-btn>
      <v-btn rounded text>Contact </v-btn>
      
<!-- 
      <v-btn icon>
        <v-icon>mdi-home</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>mdi-phone</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn> -->
    </v-app-bar>
  </div>
  </template>


  
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>