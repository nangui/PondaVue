<template>
  <div id="acceuil">
    <section>
      <div class="col1">
        <h1>Système de composant</h1>
        <p>
          Ce projet Vue va consister à créer le plus de composant réutilisable possible. Tout en gardant
          en tête l'idée que ce n'est qu'un moyen de pofiner mes connaissances en Vue.
        </p>
      </div>
      <div class="col2">
        <div class="center">
          <i class="material-icons">chevron_right</i>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Acceuil',
  data () {
    return {

    }
  }
}
</script>

<style scoped>
.center {
    text-align: center;
    margin: auto;
    width: 50% !important;
    padding: 0px;
}
.material-icons {
  font-size: 100px;
}
.material-icons:hover {
  color: blue;
}
</style>
