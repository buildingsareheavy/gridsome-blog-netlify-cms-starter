<template>
  <Layout :show-logo="true">
    <!-- Author intro -->
    <Author :show-title="true"/>

    <div class="info">
      <div class="content-box">
        <p>This is text.</p>
      </div>
    </div>
  </Layout>
</template>

<script>
import Author from "~/components/Author.vue";

export default {
  components: {
    Author
  },
  metaInfo: {
    title: "Info"
  }
};
</script>

<style lang="scss">
.info {
}
</style>

