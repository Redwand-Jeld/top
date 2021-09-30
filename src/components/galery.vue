<template>
    <div >
      
 <!-- start proyectos web -->
      <v-layout column align-center>
<h1 class="display-2 error--text Merienda" xs12 sm12 >Posts recientes</h1>

      </v-layout>
      <v-container  grid-list-md>
     
      <v-layout row wrap >
       
           

 <v-flex xs12 sm3                        
>
           <v-card to="blog/earthquakee">
              
        <v-img src="@/assets/img/earthquakee.png"></v-img>
        
                
          </v-card>  

        </v-flex>

 <v-flex xs12 sm3                        
>
           <v-card to="blog/sistem">
              
        <v-img src="@/assets/img/sistem.png"></v-img>
        
                
          </v-card>  

        </v-flex>

<v-flex xs12 sm3                        
>
           <v-card to="blog/philosofhy" >
              
        <v-img src="@/assets/img/philosofhy.png"></v-img>
        
                
          </v-card>  

</v-flex>




<v-flex xs12 sm3                        
>
           <v-card to="blog/student" >
              
        <v-img src="@/assets/img/student.png"></v-img>
        
                
          </v-card>  

</v-flex>




       



        </v-layout>
    </v-container>





       








    </div>
</template>


<style>
@import url('https://fonts.googleapis.com/css2?family=Merienda&display=swap');

</style>


<script>
import footerDev from './footerDev.vue'
export default {
  components: { footerDev },
    name: 'cards',
     
}
</script>