<template>
  <v-card color="grey lighten-2" class="ml-10 mt-10" max-width="344">
    <div align="center"><v-img src="../assets/tentativa2.png" height="170" width="185" class="ma-2"></v-img></div>

    <v-card-title>
      <h1><span color="" class="info--text">João Gomes</span><br><span class="">Bolsista</span></h1><br>
    </v-card-title><br>

    <v-card-subtitle>
      <b>Projetos: </b><br>
      <b>Turma: </b><br>
    </v-card-subtitle>

    <v-card-actions>
      <v-btn class="ma-2 black--text" color="blue-grey darken-4" text>Detalhes</v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>

        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>

</template>

<script>
  export default {
    data: () => ({
      show: false,
      pc:[
        {nome: "PC 01", nomeuser:"Felipe Mendes", hre:"18:30", hrs:"19:30", status:"Indisponível", color:'error', projeto:"Hackaton", ilha:"Ilha 01"},
        {nome: "PC 02", nomeuser:"Nenhum", hre:"Livre", hrs:"Livre", status:"Disponível", color:'success', projeto:"Nenhum", ilha:"Ilha 02"},
        {nome: "PC 03", nomeuser:"*", hre:"*", hrs:"*", status:"Manutenção", color:'warning', projeto:"*", ilha:"Ilha 03"}
      ],
    }),
  }
</script>