<template>
  <div>
 <div>
<Header />
 </div>
  <div style="height: 60px">
    <Poster />
  </div>
  </div>
</template>

<script>

import Header from "@/components/Header";
import Poster from "@/components/Poster";
export default {
  name: 'Home',
  components: {Poster, Header},
}
</script>
