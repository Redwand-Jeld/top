<template>
    <div class="blue-grey darken-4">
      
 <!-- start proyectos web -->
      <v-layout column align-center>
<h1 class="display-2 white--text Merienda pb-3 pa-5" xs12 sm12 >Planes Atomicos</h1>

      </v-layout>
      <v-container  grid-list-md>
     
      <v-layout row wrap >
       
           

 <v-flex xs12 sm4                        
>
           <v-card >
              
        <v-img src="@/assets/img/botellon.png"></v-img>
        
                
          </v-card>  

        </v-flex>

 <v-flex xs12 sm4                        
>
           <v-card >
              
        <v-img src="@/assets/img/after.png"></v-img>
        
                
          </v-card>  

        </v-flex>

<v-flex xs12 sm4                        
>
           <v-card >
              
        <v-img src="@/assets/img/anti.png"></v-img>
        
                
          </v-card>  

</v-flex>


       



        </v-layout>
    </v-container>
<!-- end proyectos web -->

 <!-- start  knownledge -->



<v-container  grid-list-md>
            <!-- aqui va una foto con @/ asset--
            -->

      <v-layout row wrap >
          <v-flex xs12 sm4  >
           <v-card>
              
              
              
                 
                
          </v-card>  
        </v-flex > 



        <v-flex xs12 sm4  >
           <v-card>

              
             
                 
          </v-card>  
        </v-flex >

 <v-flex xs12 sm4>
           <v-card>
              
             
                  
                
          </v-card>  

        </v-flex>

 




<v-flex xs12 sm4 >
           <v-card>
              
             
                
          </v-card>  
        </v-flex>

       
     <v-flex xs12 sm4  >
           <v-card>
              
              

                
          </v-card>  
        </v-flex >


      <v-flex xs12 sm4  >
           <v-card>
              
              
              
                 
                
          </v-card>  
        </v-flex >

<v-flex xs12 sm4  >
           <v-card>
              
              
              
                 
                
          </v-card>  
        </v-flex >




        </v-layout>
    </v-container>
 <!-- end  knownledge -->


 <!-- start  Learning  -->


      <v-container  grid-list-md>
     
      <v-layout row wrap >
       
           



        <v-flex xs12 sm4  >
           <v-card>
              
             
                 
                
          </v-card>  
        </v-flex >

 <v-flex xs12 sm4                       
>
<v-card>
              
              
              
                
          </v-card>  

        </v-flex>

<v-flex xs12 sm4 >
           <v-card>
              
              
                
                
          </v-card>  
        </v-flex>

       
    


      



        </v-layout>
    </v-container>


 <!-- end  Learning  -->










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