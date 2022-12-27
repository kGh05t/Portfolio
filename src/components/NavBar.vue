<template>
    <div>
        <v-app-bar   color="#25fa8c" elevation="16" fixed dark  shaped class="px-12 header relative ">
            
            <v-btn>
                <v-icon color="black" left class="mr-2 " >fa fa-user-ninja</v-icon>ninja                
            </v-btn>
            <v-spacer></v-spacer>       
               
                                                 
                    <v-btn variant="outlined" text @click="scroll('home')" class="text-black ">Home</v-btn>
                    <div class="w-[10px]"></div>
                    <v-btn variant="outlined" text @click="scroll('about')" class="text-black">About</v-btn>
                    <div class="w-[10px]"></div>
                    <v-btn variant="outlined" text @click="scroll('project')" class="text-black">Projects</v-btn>
                    <div class="w-[10px]"></div>
                    <v-btn variant="outlined" text @click="scroll('contact')" class="text-black">Contact</v-btn> 
                                
            
                   
        </v-app-bar>
    </div>
    
</template>

<script>
export default {
    methods:{
        scroll(refName){
            const element= document.getElementById(refName);
            element.scrollIntoView({behavior:"smooth"})
        }
    }
}
</script>
<style>

</style>