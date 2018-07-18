<template>
  <div class="container mx-auto p-4">
    <h1>Users</h1>
    <user-list class="mt-6"></user-list>
  </div>
</template>

<script>
import UserList from './components/UserList';

export default {
  name: `App`,
  components: {
    UserList,
  }
};
</script>