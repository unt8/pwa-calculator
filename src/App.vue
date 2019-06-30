<template>
  <b-container class="bv-example-row">

    <div class="text-cont">
      ddd
    </div>

    <div class="buttons-cont">
      <b-row class="h-25">
        <b-col>
          <b-button class="h-100" block @click="one()">1</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block>2</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block>3</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block></b-button>
        </b-col>
      </b-row>

      <b-row class="h-25">
        <b-col>
          <b-button class="h-100" block>4</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block>5</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block>6</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block></b-button>
        </b-col>
      </b-row>

      <b-row class="h-25">
        <b-col>
          <b-button class="h-100" block>7</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block>8</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block>9</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block></b-button>
        </b-col>
      </b-row>

      <b-row class="h-25">
        <b-col>
          <b-button class="h-100" block>7</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block>7</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block>8</b-button>
        </b-col>

        <b-col>
          <b-button class="h-100" block></b-button>
        </b-col>
      </b-row>

    </div>

  </b-container>
</template>

<script>
  import HelloWorld from './components/HelloWorld.vue'

  export default {
    name: 'app',
    components: {
      HelloWorld
    },
    methods: {
      one: function (event) {
        alert('Привет')
      }
    }
  }
</script>

<style>
  /*#app {*/
  /*  font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*  -webkit-font-smoothing: antialiased;*/
  /*  -moz-osx-font-smoothing: grayscale;*/
  /*  text-align: center;*/
  /*  color: #2c3e50;*/
  /*  margin-top: 60px;*/
  /*}*/


  .container {
    padding: 0;
  }
  .buttons-cont {
    height: 50vh;
  }

  .buttons-cont .col {
    padding: 0;
  }

  .buttons-cont .btn {
    border-radius: 0;
  }
  
  .buttons-cont .row {
    margin: 0;
  }
  .text-cont {
    height: 50vh;
  }
</style>
