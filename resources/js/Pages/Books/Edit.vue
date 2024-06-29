<script setup>
import Form from "./Form.vue";

const props = defineProps({
    authors:{type:Object},
    book:{type:Object},
    authorsOfBook:{type:Object},
});
</script>
  
<template>
 <Form :auth ors="authors"/>
</template>