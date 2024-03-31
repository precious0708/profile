<style lang="sass" scoped>
.my-card
  width: 300px
</style>

<template>
  <q-page padding class="column flex flex-center q-pb-xl">

    <span class="text-h2 text-weight-bolder about-me q-mb-xl">SKILLS <span class="text-green-6"></span></span>

    <div :class="!Platform.is.mobile ? 'row jsutify-center q-gutter-x-lg' : 'column q-gutter-y-lg'">
     
     

     
    
      
      <q-card class="my-card">
        <img :src="CSS"  class="css"  />

        <q-card-section>
          <div class="text-h6">CSS</div>
        </q-card-section>

        <q-card-actions class="q-pt-none">
          <q-btn flat icon="mdi-web" />
          <q-btn flat icon="mdi-github" />
        </q-card-actions>
      </q-card>

      <q-card class="my-card">
        <img :src="html"  class="html"  />

        <q-card-section>
          <div class="text-h6">HTML</div>
        </q-card-section>

        <q-card-actions class="q-pt-none">
          <q-btn flat icon="mdi-web" />
          <q-btn flat icon="mdi-github" />
        </q-card-actions>
      </q-card>


      <q-card class="my-card">
        <img :src="figma"  class="figma"  />

        <q-card-section>
          <div class="text-h6">FiGMA</div>
        </q-card-section>

        <q-card-actions class="q-pt-none">
          <q-btn flat icon="mdi-web" />
          <q-btn flat icon="mdi-github" />
        </q-card-actions>
      </q-card>

      <q-card class="my-card card-4">
        <img :src="protopie"  class="protopie"  />

        <q-card-section>
          <div class="text-h6">PROTOPIE</div>
        </q-card-section>

        <q-card-actions class="q-pt-none">
          <q-btn flat icon="mdi-web" />
          <q-btn flat icon="mdi-github" />
        </q-card-actions>
      </q-card>
      
      <q-card class="my-card card-4">
        <img :src="balsamiq"  class="balsamiq"  />

        <q-card-section>
          <div class="text-h6">BALSAMIQ</div>
        </q-card-section>

        <q-card-actions class="q-pt-none">
          <q-btn flat icon="mdi-web" />
          <q-btn flat icon="mdi-github" />
        </q-card-actions>
      </q-card>


      <q-card class="my-card card-4">
        <img :src="proto"  class="proto"  />

        <q-card-section>
          <div class="text-h6">PROTO.IO</div>
        </q-card-section>

        <q-card-actions class="q-pt-none">
          <q-btn flat icon="mdi-web" />
          <q-btn flat icon="mdi-github" />
        </q-card-actions>
      </q-card>


      
    </div>

  </q-page>
</template>

<script setup>
import { defineComponent } from 'vue';
import { Platform } from 'quasar';
import Project from 'src/assets/project.jpg';
import CSS from 'src/assets/css.jpg';
import html from 'src/assets/html.svg';
import figma from 'src/assets/figma.jpg';
import protopie from 'src/assets/protopie.jpg';
import balsamiq from 'src/assets/balsamiq.jpg';
import proto from 'src/assets/proto.jpg';

defineComponent({
  name: 'ServicePage'
});
</script>

<style>

.proto{

height: 150px;
object-fit: contain;
}
.css{

  height: 150px;
  object-fit: contain;
}

.html{

height: 150px;
object-fit: contain;
}
.figma{

height: 150px;
object-fit: contain;
}
.protopie{

height: 150px;
object-fit: contain;
}

.balsamiq{

height: 150px;
object-fit: contain;
}
.card-4{
  margin-top: 10px;
}
</style>
