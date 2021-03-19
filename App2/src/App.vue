<template>
  <section>
    <h2>My Friends</h2>
    <ul>
      <friend-contact></friend-contact>
      <friend-contact></friend-contact>
    </ul>
  </section>
</template>

<script>
import FriendContact from './Components/FriendContact.vue';
export default {
  components: { FriendContact },
  data() {
    return {
      friends: [
        {
          id: 1,
          name: "Andrea Ayala",
          phone: "7225-3923",
          email: "andreaayala@gmail.com",
        },
        {
          id: 2,
          name: "Silvia Ayala",
          phone: "7455-3923",
          email: "silayala@gmail.com",
        },
      ],
    };
  },
};
</script>
