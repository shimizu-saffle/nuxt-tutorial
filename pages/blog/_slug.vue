<script>
export default {
  async asyncData({ $content, params }) {
    // fetch our article here
    const article = await $content("blog", params.slug).fetch();
  },
};
</script>
