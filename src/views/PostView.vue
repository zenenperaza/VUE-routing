<template>
    <div class="">
      <h1>This is an Post page</h1>
      <h1>This is the Post number {{ postId }}</h1>
    </div>
  </template>

<script lang="ts" setup>
import { onMounted, ref, Ref  } from "vue";
import { useRoute } from "vue-router";

let postId:Ref<string> = ref('')

onMounted(() => {
  const route = useRoute()
  postId.value = route.params.id
})

</script>