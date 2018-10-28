<template lang="html">
<div>
  <p>Test your IDX knowledge with 30 questions from various departments.
  </br>
    Start playing to beat your colleagues on the leaderboard by typing and submitting your name. 
  </br>
    You can play multiple times. Refresh the page after completing all the questions, 
    then type and submit a modified version of your name.</p>
</div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
@import ".././main.scss";

div {
  margin: 0 0 1em 0;
}

p {
  font-size: 1.25em;
}

@media (max-width: 600px) {
  div {
    padding: 0 1em;
  }

  p {
    font-size: 1.1em;
  }
}
</style>
