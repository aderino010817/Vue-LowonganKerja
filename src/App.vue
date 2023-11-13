<script setup lang="ts">
import IntegrasiAPI from './components/IntegrasiAPI.vue';
import axios from 'axios';

async function fetchData() {
  try {
    const response = await axios.get('https://bti.id/services/btiportalcorems/api/pt-job-posts/no-auth');
    console.log("hasil", response.data);
  } catch (error) {
    console.error(error);
  }
}

console.log("say", fetchData());
fetchData()
</script>

<template>
  <div>
    <div class="bgWhite">
      <IntegrasiAPI />
    </div>
  </div>
  <div>
    <display>{{fetchData()}}</display>
  </div>
</template>