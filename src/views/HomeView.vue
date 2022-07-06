<template>
<v-app id="inspire" :style="{background:$vuetify.theme.themes.dark.background}">
<SideBar/>
<v-container>
  <NavBar/>
  <v-row>
    <v-col cols="12" sm="8">
      <v-row>
        <v-col cols="12" sm="12">
          <Overview/>
        </v-col>
        <v-col cols="12" sm="12">
          <Money/>
        </v-col>
        <v-col cols="12" sm="12">
          <Payment/>
        </v-col>
      </v-row>
    </v-col>
    <v-col cols="12">
      <Card/>
    </v-col>
  </v-row>
</v-container>
</v-app>
</template>

<script>
import SideBar from '@/components/SideBar.vue';
import NavBar from '@/components/NavBar.vue';
import Overview from '@/components/Overview.vue';
import Money from '@/components/Money.vue';
import Payment from '@/components/Payment.vue';
import Card from '@/components/Card.vue';
 

  export default {
    components: {
    SideBar,
    NavBar,
    Overview,
    Money,
    Payment,
    Card
},
  }
</script>
<style lang="scss">
.v-btn.withoutupercase {
  text-transform: none !important;
}
.v-btn:not(.v-btn--round).v-size--small{
  min-width: 30px !important;
  padding: 0 5px !important;
}
</style>