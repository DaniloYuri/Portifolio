<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar class="bg-blue-8">
     

        <q-toolbar-title>
          Quasar App
        </q-toolbar-title>

        <div> <q-tabs v-model="tab" shrink>
        <q-tab name="tab1" label="Tab 1" />
        <q-tab name="tab2" label="Tab 2" />
        <q-tab name="tab3" label="Tab 3" />
      </q-tabs></div>
      </q-toolbar>
    </q-header>
    <div class="bg-blue-4  " style="width: 100%; height: 350px;">
      <div  style="">
        <img class="q-mr-xl" src="..\css\img\img1.jpg" style="width:180px;" alt="">
      </div>
    </div>


    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from 'vue'


export default defineComponent({
  name: 'MainLayout',

  setup () {

  }
})
</script>
