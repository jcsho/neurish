<template>
  <b-container fluid>
    <b-img id="logo" src="/name-withwhitebg.png" fluid />
    <b-row align-h="center" class="mt-5">
      <b-cols cols="4">
        <b-button to="/mood">
            Next
        </b-button>
      </b-cols>
    </b-row>
  </b-container>
</template>

<script>
export default {
}
</script>

<style>
#logo {
  margin-top: 16rem;
  padding: 0 30rem 0 30rem;
}
</style>
