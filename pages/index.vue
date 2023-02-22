<template>
  <div>
    <carousel />
    <div class="container">
      <h1>Hoempage</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
  head() {
    return {
      title: "Home Page",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Nuxt Js website designing from scratch",
        },
      ],
    };
  },
};
</script>
