<template>

  
    <div>
        <!-- <div>
            <h1 class="text">Write your text here</h1>
     <v-card
    class="mx-auto "
    max-width="600"
    style="right:26%
            top:50px">
    <v-img
      class="white--text align-end"
      height="300px"
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
    >
    </v-img>

    <v-card-text class="text--primary">
      <p>Whitehaven Beach</p>
      <p>Whitsunday Island, Whitsunday Islands</p>
    </v-card-text>
  </v-card>
        </div>
        <div>
        <v-select color="#2496FF" 
           style="position: absolute;
                  width: 394px;
                  height: 48px;
                  left: 1010px;
                  top:110px;
                  box-sizing: border-box;
                  border-radius: 6px;"
                  :items="items"
                  label="Quick Review"
                  
                  outlined
                  
        ></v-select>
        </div> -->
        <v-container>
          <v-row>
            <h1 class="text">Write your text here</h1>
            <v-col lg="8"  >
              <v-card
    class="mx-auto "
    max-width="700"
    style="right:26%">
    <v-img
      class="white--text align-end"
      height="400px"
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
    >
    </v-img>

    <v-card-text class="text--primary">
      <p>Whitehaven Beach</p>
      <p>Whitsunday Island, Whitsunday Islands</p>
    </v-card-text>
  </v-card>
            </v-col>
            <v-col>
              
              <v-select color="#2496FF" 
           style="position: absolute;
                  width: 394px;
                  height: 48px;
                  left: 1010px;
                  top:110px;
                  box-sizing: border-box;
                  border-radius: 6px;"
                  :items="items"
                  label="Quick Review"
                  
                  outlined
                  
        ></v-select>
        
              
            </v-col>
            <v-col>
              
              <v-rating
      v-model="rating"
      background-color="orange lighten-3"
      color="orange"
     large
    ></v-rating></v-col>
            
          </v-row>
        </v-container>

    </div>
    
    
</template>
<script>
export default {
    data: () => ({
      items: ['Good', 'Awesome', 'Loved it', 'Not Good'],
    }),
}
</script>
<style>
.text{
        position: absolute;
        width: 652px;
        height: 122px;
        left: 100px;
        top: 40px;
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 40px;
        line-height: 66px;
        display: flex;
        align-items: center;
    }

.theme--light.v-label {
  color:red
}
.theme--light.v-icon{
  color:red
}
.theme--light.v-text-field--outlined:not(.v-input--is-focused):not(.v-input--has-state)>.v-input__control>.v-input__slot fieldset{
  color:red
}
</style>
