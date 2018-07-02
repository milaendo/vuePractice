<template>
  <div class="Skills">
    <h1> {{name}} </H1>

      <button @click="changeName" :disabled="btnState">Change Name</button>
  </div>
</template>

<script>
export default{
  name: 'Skills',
  data() {
    return {
      name: "Mila"
    }
  }
}
</script>
