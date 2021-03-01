<template>
     <div class="container">
    <b-button v-b-toggle.sidebar-variant>Today</b-button>

    <b-sidebar id="sidebar-variant" title="Sidebar" bg-variant="dark" text-variant="light" shadow>
        <div class="px-3 py-2">
            <p>Tareas en Curso:
            </p>
        </div>
    </b-sidebar>
 </div> 
</template>

<script>
export default {
  name: 'TasksSidebar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
