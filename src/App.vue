<template>
  <ul></ul>
</template>

<script>
export default {
  data() {
    return {
      storedResources: [
        {
          id: 'official-guide',
          title: 'Official Guide',
          description: 'The Official Vue.js docs',
          link: 'https://vuejs.org'
        },
        {
          id: 'google',
          title: 'google',
          description: 'Try google something',
          link: 'https://google.com'
        },
      ],
    };
  },
};
</script>
