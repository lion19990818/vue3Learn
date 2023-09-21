<template>
  <div>
    <v-toolbar>
      <v-toolbar-title>主頁頂端測試</v-toolbar-title>
      &emsp;
      <v-divider vertical></v-divider>
      &emsp;
      <router-link to="/">主頁</router-link>
      &emsp;
      <router-link to="/about">測試1</router-link>
    </v-toolbar>
    <router-view/>
  </div>
</template>