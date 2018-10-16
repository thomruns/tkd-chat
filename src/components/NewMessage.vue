<template>
  <div class="new-message">
    <form @submit.prevent="addMessage">
      <label for="new-message">New Message (press Enter to add)</label>
      <input type="text" name="new-message" v-model="newMessage">
    </form>
    <p class="red-text" v-if="feedback">{{ feedback }}</p>
  </div>
</template>

<script>
export default {
  name: 'NewMessage',
  props: ['name'],
  data() {
    return {
      newMessage: null,
      feedback: null
    }
  },
  methods: {
    addMessage() {
      if(this.newMessage) {

      } else {
        this.feedback = "Please enter a message before pressing Enter"
      }
      this.newMessage = null
    }
  }
}
</script>

