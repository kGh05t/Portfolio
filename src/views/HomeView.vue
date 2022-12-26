<template>
  <NavBar />
  <v-app id="home">
    
    <div class="bg-gradient-to-r from-red-200 via-red-300 to-yellow-200"></div>
    <particlesViewVue />
    <v-container fluid>      
      
       <div>
      <div class="absolute -mt-28 mb-6 left-0 bg-gradient-to-b from-red-200 via-red-300 to-yellow-200 h-[400px] w-1/2 skew-y-6">
        <v-row>
          <v-col cols="5">
            <div style="position: relative" class="left-64 mt-[150px] -skew-y-6">
              <h1 class="text-black text-xl">Hello,</h1>
             <h1 class="text-white text-4xl antialiased font-sans hover:font-serif">I'm Krishna</h1>
              <span class="text-black">Web Developer</span><br />

              <v-btn tile dark class="text-white mt-8" variant="outlined">
                Contact
              </v-btn>
            </div>
          </v-col>
          <v-col cols="2">
            <div class="z-80">
              <v-icon class="mt-[350px] ml-[372px] -skew-y-6  text-center items-center">fas fa-angle-double-down</v-icon>
            </div>
          </v-col>
        </v-row>
      </div>
      <div class="absolute -z-10 -mt-28 mb-6 right-0 bg-gradient-to-b from-red-200 via-red-300 to-yellow-200 h-[400px] w-1/2 -skew-y-6"></div>
    </div>
    <div class="">      
      <v-col cols="14" class="relative z-10 text-green mt-32 " id="about">
        <div>
          <div class="relative ml-32 mt-80">
      <v-img 
              lazy-src="https://picsum.photos/id/11/10/6"
              max-height="150"
              max-width="250"
              src="https://picsum.photos/id/11/500/300">
            <template v-slot:placeholder>
                    <div class="d-flex align-center justify-center fill-height">
                      <v-progress-circular
                        indeterminate
                        color="grey-lighten-4"
                      ></v-progress-circular>
                    </div>
                  </template>
</v-img></div>
          <v-row>
            <v-col cols="12" md="6">
              
            </v-col>
            <v-col class="relative -mt-60 ml-120" cols="12" sm="4">
              <h2 class="mt-16 font-bold text-4xl text-yellow">About Me</h2>
              <div style="width: 170px">
                <v-slider
                  v-model="slider2"
                  color="red"
                  label=""
                ></v-slider>
              </div>
              <h4 class="mt-n4">I Am a Web Developer</h4>
             
              <p class="text-indigo">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Aspernatur, ullam perspiciatis fugiat temporibus laboriosam
                accusamus tempora repellendus sequi sed cum dolorum vero est.
                Placeat dicta architecto reiciendis est veniam. Unde.
              </p>
              <br />
              <p class="text-indigo">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Aspernatur, ullam perspiciatis fugiat temporibus laboriosam
                accusamus tempora repellendus sequi sed cum dolorum vero est.
                Placeat dicta architecto reiciendis est veniam. Unde.
              </p>
              <v-btn tile dark color="green" class="mt-4" id="project">
                Download Resume
              </v-btn>
            </v-col>
          </v-row>
        </div>
      </v-col>
      </div>
      <div class="relative mt-16 text-center " id="projecty">
        <h1 class="font-bold text-4xl text-yellow " >Projects</h1>
        <div style="width: 140px; margin: 0 auto">
          <v-slider
            v-model="slider2"
            color="red"
            label=""
          ></v-slider>
        </div>
      </div>
      <v-col cols="64" class="relative align-middle ml-64" id="port">
        <div class="first align-middle ml-80" >
          <v-row class="relative m-4">
            <v-col cols="4">
              <v-row class="">
              <div class="child align-middle text-center ">
                <v-btn
                  icon="fas fa-laptop"
                  color="#FBDF7E"
                  class="text-white mt-4"
                ></v-btn>
                <h3 class="text-white ml-0 mt-4">Porodictor</h3>
                <p class="text-blue ml-3 mt-4 text-caption">
                  Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                  <br />consectetur adipis
                </p>
              </div>
            </v-row>
              <v-row>
              <div class="child align-middle text-center">
                <v-btn
                  icon="fas fa-mobile-alt"
                  color="#FBDF7E"
                  class="text-white mt-4"
                ></v-btn>
                <h3 class="text-white ml-3 mt-4">Home Automation</h3>
                <p class="text-blue ml-3 mt-4 text-caption">
                  Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                  <br />consectetur adipis
                </p>
              </div>
            </v-row>
            <v-row>
              <div class="child align-middle text-center">
                <v-btn
                  icon="fas fa-camera"
                  color="#FBDF7E"
                  class="text-white mt-4"
                ></v-btn>
                <h3 class="text-white ml-3 mt-4">Excel-to-Word</h3>
                <p class="text-blue ml-3 mt-4 text-caption" id="contact">
                  Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                  <br />consectetur adipis
                </p>
              </div>
            </v-row>
            </v-col>
          </v-row>
          <v-divider></v-divider>
        </div>
      </v-col>

      <v-col cols="12" sm="12" class="px-16 z-10 mt-4" id="contact1">
        <v-row>
          <v-col cols="12" sm="4">
            <div class="child text-cyan font-bold">
              <h1 class="font-bold text-4xl text-red ">Contact info.</h1>
              <v-btn
                icon="fas fa-map-marker-alt"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">Indira Colony Chandausi (244412)</span
              ><br />
              <v-btn
                icon="fas fa-phone-alt"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">+917017417380 </span> <br />
             
              <v-btn
                icon="fas fa-envelope"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">krishna16425@gmail.com </span> <br />
              
            </div>
            
          </v-col>
          <v-col class="text-white text-bold -mt-0" cols="12" sm="8">
            <h1 class=" text-4xl text-bold text-red -mt-4">Send your message</h1>
            <v-divider></v-divider>
            <span class="text-caption"
              >random text pk pkpk jbiuhiug i h u hkjh uiohoi uyh iyvyyuuyyugy gy gy gigi</span
            >
            <v-row class="mt-10">
              <v-col cols="12" sm="6">
                <v-text-field  flat solo
                  label="Name"                  
                  variant="outlined"
                ></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Phone No"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
            </v-row>
            <v-textarea
              label="Message"
              persistent-hint
              variant="outlined"
            ></v-textarea>
            <v-btn color="#FBDF7E" class="mt-2  text-black">Submit Now</v-btn>
          </v-col>
          </v-row>
      </v-col>      
    </v-container>
    <FooterViewVue/>
  </v-app>

</template>

<script>
import { defineComponent } from 'vue';

// Components
import NavBar from '@/components/NavBar.vue'
import particlesViewVue from '@/components/particlesView.vue'
import FooterViewVue from '@/components/FooterView.vue';
export default defineComponent({
  name: 'HomeView',

  components: {
    
    NavBar,
    particlesViewVue,
    FooterViewVue

  },
});
</script>
<style scoped>

/* .v-container{
  padding:16px 0;  
}
.head{
  text-align: center;
  padding:12px;
  margin-bottom: 6px;
  height:400px;
  width:100%;
  color:white;
} */

</style>
