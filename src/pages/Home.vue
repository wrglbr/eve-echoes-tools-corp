<template>
  <Layout>
    <template #default>
      Default content
    </template>
    <template #footer>
      <p>Footer uno</p>
    </template>
  </Layout>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import Layout from '@/components/Layout'

export default defineComponent({
  name: 'Home',
  components: {
    Layout
  }
})
</script>
