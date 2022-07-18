<template>
  <div class="flex">
    <Accolades />
    <Form />
  </div>
</template>

<script>
import Accolades from './components/Accolades.vue';
import Form from './components/Form.vue';


export default {
    name: "App",
    components: { Accolades, Form }
}
</script>