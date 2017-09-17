<template>
  <div>
    <b-container fluid class="mt-5 pl-5">
      <b-row>
        <b-col>
          <b-button to="/">back</b-button>
        </b-col>
      </b-row>
      <b-row align-h="center" class="heading">
        <b-col cols="9">
          <h1>I want to feel...</h1>
        </b-col>
      </b-row>
    </b-container>

    <b-container class="moods">
      <b-row class="top-row">
        <b-col cols="4">
          <b-button id="happy" variant="link" to="/mood/happy">
            <b-img class="icons" src="/icons/happy.png" />
          </b-button>
        </b-col>
        <b-col cols="4">
          <b-button id="balanced" variant="link" to="/mood/balanced">
            <b-img class="icons" src="/icons/balanced.png" />
          </b-button>
        </b-col>
        <b-col cols="4">
          <b-button id="relaxed" variant="link" to="/mood/relaxed">
            <b-img class="icons" src="/icons/relaxed.png" />
          </b-button>
        </b-col>
      </b-row>

      <b-row class="bot-row">
        <b-col cols="4">
          <b-button id="energized" variant="link" to="/mood/energized">
            <b-img class="icons" src="/icons/energized.png" />
          </b-button>
        </b-col>
        <b-col cols="4">
          <b-button id="focused" variant="link" to="/mood/focused">
            <b-img class="icons" src="/icons/focused.png" />
          </b-button>
        </b-col>
        <b-col cols="4">
          <b-button id="awake" variant="link" to="/mood/awake">
            <b-img class="icons" src="/icons/awake.png" />
          </b-button>
        </b-col>
      </b-row>

      <b-tooltip target="happy" title="Happy!"></b-tooltip>
      <b-tooltip target="balanced" title="Balanced"></b-tooltip>
      <b-tooltip target="relaxed" title="Relaxed~"></b-tooltip>
      <b-tooltip target="energized" placement="bottom">ENERGIZED!</b-tooltip>
      <b-tooltip target="focused" placement="bottom">f o c u s e d</b-tooltip>
      <b-tooltip target="awake" placement="bottom">!! awake !!</b-tooltip>
    </b-container>
  </div>
</template>

<script>
export default {

}
</script>

<style>
h1 {
  font-family: Comfortaa;
}
.heading {
  margin-top: 5rem;
}
.moods {
  margin-top: 5rem;
}

.bot-row {
  margin-top: 5rem;
}

.icons {
  width: 30%;
}
</style>
