<template>
<div>
<parallax/>
<down/>
 <cards/>
<galery/>
</div>
  
</template>

<script>
import cards from '@/components/cards.vue'
import footerDev from '@/components/footerDev.vue'
import parallax from '@/components/parallax.vue'
import Galery from '../components/galery.vue'
import down from '@/components/down.vue'

  export default {
    name: 'Home',

    components: {
      
      cards,
      footerDev,
      parallax,
        Galery,
        down    }
    
  }
</script>
