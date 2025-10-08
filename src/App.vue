<script setup>
const message = { name: "Kim", age: 20 };
</script>

<template>
<span>Hello </span>
<span v-text="JSON.stringify(message)"></span>
</template>