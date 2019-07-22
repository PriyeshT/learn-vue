<template>
  <div class="about">
    <h1>This is an about page</h1>
    <BlockQuote quote="testing blockquote creation using vue" />
  </div>
</template>

<script>
import BlockQuote from '@/components/BlockQuote.vue'

export default {
  name: 'about',
  components: {
    BlockQuote
  }
}
</script>

