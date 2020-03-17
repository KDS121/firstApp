<template>
<nav>
    <v-app-bar
      color="FFFFFF"
      fixed
    >
      <v-app-bar-nav-icon @click="drawer =! drawer"> </v-app-bar-nav-icon>
      <v-img src="../assets/icon.svg"
       max-height="60"
       contain
       class=icon>
       </v-img>
      <v-text-field 
        flat
        solo-inverted
        hide-details
        prepend-inner-icon="mdi-magnify"
        label="Search.."
        class="hidden-sm-and-down searchbox"
      />
      
    <v-spacer></v-spacer>     
    </v-app-bar>
    
    <v-navigation-drawer  v-model="drawer" app class="indogo xyz" color="#2496FF" width="80px"> 
     <v-app-bar-nav-icon @click="drawer =! drawer" color="white" class="navicon mx-4 my-4"> </v-app-bar-nav-icon>
    <v-list class="list" >
        <v-list-title>
            <v-list-title-action>
                <v-img src="../assets/homeicon.svg"></v-img>            
            </v-list-title-action>     
            <v-list-title-action>
                <v-img src="../assets/settings.svg"></v-img>            
            </v-list-title-action>   
            <v-list-title-action>
                <v-img src="../assets/user.svg"></v-img>            
            </v-list-title-action> 
             <v-list-title-action>
                <v-img src="../assets/phone.svg"></v-img>            
            </v-list-title-action>   
        </v-list-title>    
    </v-list>
    </v-navigation-drawer>
  </nav>
</template>

<script>
export default{
    data(){
        return{
            drawer: false
        }
    }
}
</script>

<style>
.navicon{
    transform : rotate(90deg);
}
.xyz{
    box-shadow: 2px 0px 4px rgba(78, 78, 78, 0.25);
    border-radius : 0px;
    border:0;    
}
.searchbox{
   position: absolute;
left: 76.04%;
right: 1.46%;
top: 14.00%;
bottom: 24.73%;
background: #FAFAFA;
border-radius: 11px;
}
.icon{
 position: absolute;
 width: 103.45px;
 height: 50px;
 left: 190px;
 top: 4px;
}
.list{
    width: 70%;
    margin: 6px;
}
</style>
