<template>
   <v-container
    class="fill-height"
    fluid
    style="min-height: 434px"
  >
    <v-fade-transition mode="out-in">
      <v-row>
        <v-col cols="6">
          <v-card>
           <img src="../assets/Pic1.jpg" alt="Profile Picture" class="profile-pic">
            <v-card-title class="text-h6">
              My Favorite
            </v-card-title>
          </v-card>
        </v-col>

        <v-col cols="6">
          <v-card>
            <img src="../assets/Pic2.jpg" alt="Profile Picture" class="profile-pic">
            <v-card-title class="text-h6">
              Mini Project IOT Smart Windows
            </v-card-title>
          </v-card>
        </v-col>

        <v-col cols="6">
          <v-card>
            <img src="../assets/Pic3.jpg" alt="Profile Picture" class="profile-pic">
            <v-card-title class="text-h6">
              Desing App Ui Biginner
            </v-card-title>
          </v-card>
        </v-col>

        <v-col cols="6">
          <v-card>
             <img src="../assets/Pic4.jpg" alt="Profile Picture" class="profile-pic">
            <v-card-title class="text-h6">
              My Favorite football team Muangthong United
            </v-card-title>
          </v-card>
        </v-col>
      </v-row>
    </v-fade-transition>
  </v-container>
</template>

<script>
export default {
   name: 'HelloWorld',

   data: () => ({
      
   })
}
</script>

<style>
   .profile-pic {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        margin: 0 auto;
        display: block;
        object-fit: cover;
      }
</style>