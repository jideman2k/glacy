<template>
  <div class="container">
    <Navbar />
  </div>
</template>
<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Chat",
  components: {
    Navbar,
  },

  setup() {
    return {};
  },
};
</script>
<style>
nav {
  padding: 20px;
  border-bottom: 1px solid #eee;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav p {
  margin: 2px auto;
  font-size: 16px;
  color: #444;
}

nav p.email {
  color: #999;
  font-size: 14px;
}

nav span.email {
  text-decoration: underline;
}
</style>
