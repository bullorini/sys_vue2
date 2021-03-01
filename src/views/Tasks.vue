<template>
  <div class="tasks">
        <TasksSidebar/>
        <TasksAdd/>
  </div>
</template>

<script>
// @ is an alias to /src
import TasksSidebar from '@/components/TasksSidebar.vue'
import TasksAdd from '@/components/TasksAdd.vue'

export default {
  name: 'Tasks',
  components: {
    TasksSidebar,
    TasksAdd
  }
}
</script>