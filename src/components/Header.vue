<template>
  <div>
    <b-nav tabs style="display: flex; justify-content: center; align-items: center;">
      <b-nav-item disabled><b>Vue Quiz App</b></b-nav-item>
      <b-nav-item disabled>Counter: {{ numCorrect }}/{{ numTotal }}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: [
    'numCorrect',
    'numTotal'
  ]
}
</script>