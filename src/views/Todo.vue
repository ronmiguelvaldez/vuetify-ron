<template>
  <div class="todo pa-6 ma-10">
    <h1> Todo Page</h1>
    <v-form>
      <v-autocomplete
      label="Todo List"
      :items="['Enroll Biometrics','Get BDO Card', 'Learn Code Igniter', 'Study Vue JS', 'Study MySQL',]"
      v:model="input"
      >
    </v-autocomplete>
    <v-btn color="primary" class="mr-1" @click="addList">Add List</v-btn>
    <v-list lines="one">
    </v-list>
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
        
      }
    },
    methods: {
      
    }
  }
</script>
