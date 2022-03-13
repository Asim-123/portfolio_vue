<template>
<Appheader />
<Apphome />
<Appabout />
<Appresume />
<Appservice />
<appcontact />
</template>

<script>

import Appheader from './components/Appheader.vue'
import Apphome from './components/Apphome.vue'
import Appabout from './components/Appabout.vue'
import Appresume from './components/Appresume.vue'
import Appservice from './components/Appservice.vue'
import Appcontact from './components/Appcontact.vue'
export default {
  name: 'App',
  components: {
   Appheader,
   Apphome,
   Appabout,
   Appresume,
   Appservice,
   Appcontact

  
  }
}
</script>

<style>

</style>
