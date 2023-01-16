<template>
    <div>
        <button id="myBtn" @click="mySecondFunction" @dblclick="myFourthFunction" @mouseout="myThirdFunction" @mouseover ="myFunction">Try it</button> <br>
        <!-- Type URL : <input type=text, name = "x" id="" v-model="newurl" >   -->
        <p id="demopage"> </p>
        
    </div>
  
  </template>
  
<script>

export default{
    
    
    methods:{
        myFunction() {
            document.getElementById("demopage").innerHTML += "Moused over!<br>";
        },

        mySecondFunction() {
            document.getElementById("demopage").innerHTML += "Clicked!<br>";
        },

        myThirdFunction() {
            document.getElementById("demopage").innerHTML += "Moused out!<br>";
        },

        myFourthFunction() {
            var i ;
            document.getElementById("demopage").innerHTML += "Double Clicked!<br>";
            // window.open()
            
        }
    }
    
}
</script>
  

<style>
  
  
</style>