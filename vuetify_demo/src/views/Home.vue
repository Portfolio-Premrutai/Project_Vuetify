<template>
  <div id="home">
    <!-- fluid กระจายเต็ม -->
    <v-container fluid>
      <div v-if="false">
        <h1>Home</h1>
        <!-- code color not working -->
        <p class="sai lighten-3 red--text text--darken-4">Premrutai</p>
        <p class="text-uppercase">Khamchalee</p>
        <h1 class="display-4">Premrutai</h1>
        <p class="caption">Premrutai</p>
        <p class="title font-weight-thin">Premrutai</p>
        <v-btn fab depressed class="pink white--text mr-10">Run</v-btn>
        <v-btn small depressed class="pink white--text mr-5">Run</v-btn>
        <v-btn outlined color="pink" class="mr-5"
          >Run <v-icon>info</v-icon></v-btn
        >
        <v-btn text color="pink" class="mr-5">Run <v-icon>info</v-icon></v-btn>
        <v-btn outlined color="pink" class="mr-5">
          <v-icon left size="30">email</v-icon>
          <span>Email</span>
        </v-btn>
        <!-- Breakpoint -->
        <v-container>
          <v-btn color="success" class="hidden-sm-and-up ma-2"
            >Only show in SM and XS</v-btn
          >
          <v-btn color="success" class="hidden-md-only ma-2"
            >Only show in Md</v-btn
          >
          <v-btn color="success" class="hidden-md-and-down"
            >Hidden when smaller than md</v-btn
          >
        </v-container>
      </div>
      <!--no-gutters ตัดช่องไฟ  -->
      <v-row no-gutters>
        <v-col cols="6" md="4">
          <v-btn outlined block color="success">Text1</v-btn>
        </v-col>
        <v-col cols="6"  md="4">
          <v-btn outlined block color="success">Text2</v-btn>
        </v-col>
            <v-col cols="12" sm="6" md="4">
          <v-btn outlined block color="success">Text3</v-btn>
        </v-col>
      </v-row>
      <!-- flex demo justify การกระจาย object -->
      <v-row no-gutters class="justify-center align-content-center" style="height:200px;background-color:#990000;">
        <v-col cols="2" >
          <v-btn  block color="success">Text1</v-btn>
        </v-col>
        <v-col cols="2"  >
          <v-btn  block color="success">Text2</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "home",
};
</script>

<style></style>
