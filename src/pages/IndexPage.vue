<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
  </div>
  <InputPage></InputPage>
  <FunctionPage></FunctionPage>


</template>


<script>
import InputPage from "./InputPage.vue";
import FunctionPage from "./FunctionPage.vue";

export default {
    name: 'HtmlComponent',
    data() {
        return {
            title: 'ธนกร แย้มศิริ',
        };
    },
    components: { InputPage,FunctionPage }
}
</script>

<style scoped></style>
