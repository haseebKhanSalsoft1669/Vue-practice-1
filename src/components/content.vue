<template>
<div class="content-area">

    <div class="container">
        <div class="row">
            <div class="col-md-4" v-for="(box,index) in boxes" :key="index">
                <box :box="box"/>
            </div>
        </div>

        <div class="row">
            <div class="col-md-6" v-for="(boxhalf,index) in Halfbox" :key="index">
                <half-box-component :twoboxes="boxhalf"/>
            </div>
        </div>
    </div>
</div>
</template>


<script>
import Box from "./box";
import HalfBoxComponent from "./boxhalf";

export default {
  name: "app",
  components: {Box, HalfBoxComponent},
  data(){
      return {
          boxes: [
              {
                  title: 'Title 1',
                  image: 'client-profile-img.jpg',
                  description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s'
              },
              {
                  title: 'Title 2',
                  image: 'client-profile-img.jpg',
                  description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s'
              },
              {
                  title: 'Title 3',
                  image: 'client-profile-img.jpg',
                  description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s'
              }
          ],
          Halfbox: [
              {
                  title: 'Title 2222',
                  image: 'client-profile-img.jpg',
                  description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s'
              },
              {
                  title: 'Title 2',
                  image: 'client-profile-img.jpg',
                  description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s'
              }
          ]
      }
  }
};
</script>


<style>
.content-area{
    padding:50px 0;
}
</style>