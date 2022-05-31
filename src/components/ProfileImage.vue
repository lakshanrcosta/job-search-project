<template>
  <img
    :src="imageURL"
    alt="Profile Picture"
    class="w-8 h-8 object-contain rounded-3xl"
  />
</template>

<script>
export default {
  name: "ProfileImage",
  data() {
    return {
      imageURL:
        "https://avatars.githubusercontent.com/u/105753470?s=400&u=9f86ea9574118951d65114b3dc424f9978d83c59&v=4",
    };
  },
};
</script>
