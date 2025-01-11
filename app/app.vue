<script setup lang="ts">
  // import {
  //   initAccordions,
  //   initCarousels,
  //   initCollapses,
  //   initDials,
  //   initDismisses,
  //   initDrawers,
  //   initDropdowns,
  //   initModals,
  //   initPopovers,
  //   initTabs,
  //   initTooltips,
  // } from 'flowbite'

  // initialize components based on data attribute selectors
  // initialize only those components that are used in your app
  // onMounted(() => {
  //   useFlowbite(() => {
  //     initAccordions()
  //     initCarousels()
  //     initCollapses()
  //     initDials()
  //     initDismisses()
  //     initDrawers()
  //     initDropdowns()
  //     initModals()
  //     initPopovers()
  //     initTabs()
  //     initTooltips()
  //   })
  // })
</script>

<template>
  <div>
    <NuxtLoadingIndicator />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<style></style>
