<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <img alt="example result" src="../assets/contribution-activity.png">
    <h3>Choose a word</h3>
    <ul>
      <li>not more than 10 symbols to fit it on one screen</li>
      <li>this word will represent your profile, so be caution in your choise</li>
    </ul>
    <h3>Find a starting week</h3>
    <ul>
      <li>to tell the algorithm where to start painting points</li>
      <li>can be chosen just a number of the week in a month</li>
      <li>make sure that the text will not overlay with other activity in the account</li>
    </ul>
    <h3>Give access to the account</h3>
    <ul>
      <li>default repository name is <strong>guthub-brush-activity</strong> can be changed of course</li>
      <li>the repository is automatically created</li>
      <li>the repository can be automatically deleted to recreate activity with another starting date or another word</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'GettingStarted',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 5rem;
}
h3 {
  font-size: 2rem;
  margin: 3rem 0 0;
}
ul {
  padding: 0;
}
li {
  margin: 1rem;
}
a {
  color: #42b983;
}
img {
  max-height: unset;
}
</style>
