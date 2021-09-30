<template>
<div>

   <v-app-bar color="black" dense dark>
    <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
<v-layout column row  pa-5  >

    
      <h1 class="yellow--text">Atom Task</h1>

 
  

                
     </v-layout>
     
        
        <v-spacer></v-spacer>
        <a  href="https://discord.gg/rS7at7ZSZh" target="_blank" class="black--text">
        <v-btn icon color="deep-purple accent-2
">
          <v-icon>mdi-discord</v-icon>
        </v-btn></a>

        

        <a href="https://www.instagram.com/atomic_task/" rel="noopener noreferrer" class="black--text">
        <v-btn icon color="pink">
          <v-icon>mdi-instagram</v-icon>
        </v-btn>
        </a>

        <a href="
https://exp-shell-app-assets.s3.us-west-1.amazonaws.com/android/%40ibluday/att-fd4042a490ac46d58962e9c496f2673e-signed.apk        "  rel="noopener noreferrer" class="black--text">

        <v-btn icon color="yellow" >
          <v-icon>mdi-download-box</v-icon>
        </v-btn>        </a>


      </v-app-bar>

       <v-navigation-drawer
      v-model="drawer"
      absolute
      temporary
      dark
            class="black "

    >
      <v-divider></v-divider>

      <v-list dense >
        
  <v-list-item to="/"

        >
          <v-list-item-icon>
            <v-icon>mdi-home</v-icon>
          </v-list-item-icon>

          <v-list-item-content  >
            

            <v-list-item-title >Inicio</v-list-item-title>

          </v-list-item-content>
        </v-list-item>



        <v-list-item to="/route"

        >
          <v-list-item-icon>
            <v-icon>mdi-view-dashboard</v-icon>
          </v-list-item-icon>

          <v-list-item-content  >
            

            <v-list-item-title >Ruta atomica</v-list-item-title>

          </v-list-item-content>
        </v-list-item>


        <v-list-item to="/blog"

        >
          <v-list-item-icon>
            <v-icon>mdi-book-variant</v-icon>
          </v-list-item-icon>

          <v-list-item-content  >
            

            <v-list-item-title >Consejos atomico</v-list-item-title>

          </v-list-item-content>
        </v-list-item>

               <a href="
https://exp-shell-app-assets.s3.us-west-1.amazonaws.com/android/%40ibluday/att-fd4042a490ac46d58962e9c496f2673e-signed.apk               ">

        <v-list-item>

          <v-list-item-icon>
            <v-icon>mdi-download
</v-icon>
          </v-list-item-icon>

          <v-list-item-content  >
            

            <v-list-item-title >
            
              Descargar</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
    
 </a>



        <v-list-item to="/help"

        >
          <v-list-item-icon>
            <v-icon>mdi-help-box

</v-icon>
          </v-list-item-icon>

          <v-list-item-content  >
            

            <v-list-item-title >Ayuda</v-list-item-title>

          </v-list-item-content>

        </v-list-item>



<v-list-item to="/policy"

        >
          <v-list-item-icon>
            <v-icon>mdi-newspaper

</v-icon>
          </v-list-item-icon>

          <v-list-item-content  >
            

            <v-list-item-title >Politica de Privacidad </v-list-item-title>

          </v-list-item-content>

        </v-list-item>



      </v-list>

    </v-navigation-drawer>
      
</div>
</template>

<script>
name:"navbar"
  export default {
    data () {
      return {
        drawer: null,
        
      }
    },
  }
</script>