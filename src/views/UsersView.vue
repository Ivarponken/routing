<script setup>
document.title = 'Users'
// import UserCard from '@/components/UserCard.vue'
// import kjell from '@/assets/images/kjell.png'
import userData from '@/assets/data/users.json'
import { ref } from 'vue'
import UsersList from '@/components/UsersList.vue'
const users = ref(userData)
</script>
<template>
  <div class="users">
    <h1>Användarsida</h1>
  </div>
  <UsersList :user-list="users" />
</template>
<style scoped></style>
