<template>

  <div class="message">
    <h2>Suivez notre actualité&nbsp;!</h2>

    <p>DesignGouv, c’est aussi des événements, des rencontres et des discussions pour faire vivre la culture design au sein des administrations. Rejoignez-nous&nbsp;!</p>

    <g-link class="button" to="/newsletter" title="Je m'inscris à la newsletter - Nouvelle fenêtre">Je m'inscris à la <span lang="en">newsletter</span></g-link>

    <p>Sur Twitter : <a href="https://twitter.com/design_gouv" title="Twitter DesignGouv - Nouvelle fenêtre" target="_blank">@design_gouv</a></p>
  </div>

</template>


<script>

  export default {
    name: 'Newsletter'
  }

</script>


<style lang="scss">

  .message {
    margin-top: 80px;

    .button {
      margin-bottom: 0;
    }
  }

</style>
