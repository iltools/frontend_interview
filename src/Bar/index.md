---
group: 数据录入
title: AutoComplete 自动完成
order: 1
---

# AutoComplete 自动完成

This is an example component of Vue SFC.

```vue
<script setup>
import { ref } from 'vue';
import { Bar } from 'iltools-frontend-interview';

const color = ref('red');
</script>

<template>
  <p class="greeting">
    <Bar icon="🤙">Hello Vue!</Bar>
  </p>
</template>

<style>
.greeting {
  color: v-bind('color');
  font-size: 16px;
  font-weight: bold;
}
</style>
```
## Bar API

### Props

<API id="Bar" type="props"></API>

### Slots

<API id="Bar" type="slots"></API>

### Events

<API id="Bar" type="events"></API>
