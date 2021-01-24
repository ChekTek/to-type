<template>
  <h1>To Type</h1>
  <TextBox v-model:text="inputText"/>
  <TextBox v-model:text="outputText"/>

  <h2>Test</h2>
  {{inputText}}
  <hr>
  {{outputText}}
</template>

<script>
import TextBox from './components/TextBox.vue'

export default {
  name: 'App',
  data: ()=> ({
    inputText: 'Input',
    outputText: 'Output'
  }),
  components: {
    TextBox
  }
}
</script>
