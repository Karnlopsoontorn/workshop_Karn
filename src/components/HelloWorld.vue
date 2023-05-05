<template>
   <v-container>

     <br /> <br />
      <h1>Sawat Dee kub pee </h1>
      <br /> <br />
      <v-card
    class="mx-auto"
    max-width="344"
  >
    <v-card-text>
      <div>Phom Chue</div>
      <p class="text-h4 text--primary">
        Karn
      </p>
      <p>Chuelen</p>
      <div class="text--primary">
         Lion Chop Len game Lae Ko Chop Ta ball kub
      </div>
    </v-card-text>
    <v-card-actions >
      <v-btn
        variant="text"
        color="teal-accent-4"
        value to = "/Profile"
      >
        Learn More
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <v-card
        v-if="reveal"
        class="v-card--reveal"
        style="height: 100%;"
      >
        <v-card-text class="pb-0">
          <p class="text-h4 text--primary">
            Origin
          </p>
          <p>late 16th century (as a noun denoting a place where alms were distributed): from medieval Latin eleemosynarius, from late Latin eleemosyna ‘alms’, from Greek eleēmosunē ‘compassion’ </p>
        </v-card-text>
        <v-card-actions class="pt-0">
          <v-btn
            variant="text"
            color="teal-accent-4"
            @click="reveal = false"
          >
            Close
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-expand-transition>
  </v-card>
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
.v-card--reveal {
  bottom: 0;
  opacity: 1 !important;
  position: absolute;
  width: 100%;
}
.container{
  margin: auto;
  width: 50%;
  padding: 10px;
}
.v-card-actions.v-btn{
  margin: auto;
  width: 50%;
  padding: 10px;
}

</style>
