<script setup lang="ts">
import { useRouter } from 'vue-router'

const name = ref('')

const router = useRouter()
const go = () => {
  if (name.value)
    router.push(`/hi/${encodeURIComponent(name.value)}`)
}
</script>

<template>
  <main>
    <aside class="grid-item sidebar">
      <div>sidebar</div>
    </aside>
    <section>
    </section>
  </main>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
