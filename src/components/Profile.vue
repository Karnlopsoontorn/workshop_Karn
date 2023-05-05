<template>
   <v-container>
      
      <h1>My Profile</h1>
    <br /> <br />
    <img src="../assets/Pic1.jpg" alt="Profile Picture" class="profile-pic">
    <br /> <br />
    <div class="profile-info">
        <br />
      <h2>Karn Lopsoontorn</h2>
       <br />
      <p>Age 21</p>
       <br />
      <p>Skill CSS HTML </p>
       <br />
    </div>
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
        width: 200px;
        height: 200px;
        border-radius: 50%;
        margin: 0 auto;
        display: block;
        object-fit: cover;
      }
</style>
