<template lang="html">
<div>
 <h2>IDX triv·i·a</h2>
  <p> Start playing to beat your colleagues on the leaderboard by typing and submitting your name. 
<p>We love trivia and IDX, thought that you might too.</p>	  </br>
    You can play multiple times.</p>
  <p>Powered by Frankie and Nichole.</p>
  <p>Source on Github</p>
</div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
@import ".././main.scss";

div {
  background-color: $color-darkest;
  margin-bottom: 2em;
  //padding-bottom: 2em;
  width: 100%;
  //height: 200px;
}

h2 {
  font-weight: bold;
}

h3 {
  color: $color-med;
  font-weight: bold;
}
p:last-child {
  margin-bottom: 2em;
}
</style>
