<template>
    <div class="about">
      <h1>This is an Blog page</h1>
      <ul>
        <li><router-link :to="{ name: 'post', params: { id: 1} }">Primer post</router-link> </li>
        <li><router-link :to="{ name: 'post', params: { id: 2} }">2 post</router-link></li>
        <li><router-link :to="{ name: 'post', params: { id: 4} }">3 post</router-link></li>
        <li><router-link :to="{ name: 'post', params: { id: 3} }">4 post</router-link></li>
      </ul>
    </div>
  </template>
  