
<template>
<v-parallax src="/pic/back.jpg"  >
  <div>
    <br>
      <router-link :to="{ path: '/student'}" replace><center>
      <div class="text-xs-center">
        <v-btn round color="black" dark>Welcome</v-btn>
      </div>
    </center>
    </router-link>
  </div>

</v-parallax>

</template>

<script>
export default {
  layout : "default",
  data() {
    return {
      id: 1,
    }
  },
}
</script>
