<template>
<v-app-bar color="transparent" flat class="mt-2">
    <div>
        <h4 class="white--text mt-n3">Good After noon</h4>
        <br/>
        <p class="grey--text caption mt-n5">let's message you save now</p>
    </div>
    <v-text-field label="search anything here" filled prepend-inner-icon="mdi-magnify" dense solo flat background-color="#1d1c21" dark class="ml-5"></v-text-field>
<v-spacer></v-spacer>
<v-icon color="#878A94" class="mt-n8">far fa-envelope</v-icon>
<v-badge bordered overlap color="red" content="2" class="ml-3 mt-n8" dark>
    <v-icon color="#878A94" >far fa-bell</v-icon>
</v-badge>
<v-avatar size="30" class="ml-3 mt-n8">
    <v-img src="https://cdn.vuetifyjs.com/images/lists/1.jpg"></v-img>
</v-avatar>
<div>
    <p class="ml-2 mt-n3 caption white--text">me account</p>
    <br/>
    <p class="ml-2 mt-n10 caption grey--text">Be beging</p>
</div>
<v-icon x-small color="#878A94" class="mt-n8 ml-2">fas fa-chevron-down</v-icon>
</v-app-bar>

</template>

<script>
export default {

}
</script>

<style>

</style>