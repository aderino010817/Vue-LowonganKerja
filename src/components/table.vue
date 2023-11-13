<template>
  <div class="table">
    <div class="row" v-for="item in items" :key="item.id">
      <div class="column">{{ item.column1 }}</div>
      <div class="column">{{ item.column2 }}</div>
    </div>
  </div>
</template>

<style>
.table {
  display: flex;
  flex-direction: column;
  border-collapse: collapse;
}

.row {
  display: flex;
  border: 1px solid #000;
}

.column {
  flex: 1;
  padding: 10px;
  border-right: 1px solid #000;
}

.column:last-child {
  border-right: none;
}
</style>

<script lang="ts">


export default {
  data() {
    return {
      items: [
        { id: 1, column1: 'Value 1', column2: 'Value A' },
        { id: 2, column1: 'Value 2', column2: 'Value B' },
        { id: 3, column1: 'Value 3', column2: 'Value C' },
      ],
    };
  },
};
</script>