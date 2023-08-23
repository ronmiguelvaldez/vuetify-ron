<template>
  <div class="todo pa-6 ma-10">
    <h1> Todo Page</h1>
    <v-form>
      <v-autocomplete
      label="Add a Task"
      :items="tasks"
      v:model="input"
      outlined
      >
    </v-autocomplete>
    <v-btn color="primary" class="mr-1" @click="addList">Add List</v-btn>
  </v-form>
      
  </div>
</template>

<script>
  export default {
    name: 'Home',
    components: {

    },
    data() {
      return {
        tasks: ['Enroll Biometrics', 'Get BDO Card', 'Learn Code Igniter', 'Study Vue JS', 'Study MySQL']
      }
    },
    methods: {
      
    }
  }
</script>
