<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup lang="ts">

useSeoMeta({
  title: 'My Amazing Site',
  ogTitle: 'My Amazing Site',
  description: 'This is my amazing site, let me tell you all about it.',
  ogDescription: 'This is my amazing site, let me tell you all about it.',
  ogImage: 'https://bityrummy.in/wp-content/uploads/2023/11/snapedit_1699357069316.png',
  ogImageAlt: 'Preview of My Amazing Site',
  twitterCard: 'summary_large_image',
  twitterTitle: 'My Amazing Site',
  twitterDescription: 'This is my amazing site, let me tell you all about it.',
  twitterImage: 'https://bityrummy.in/wp-content/uploads/2023/11/snapedit_1699357069316.png',
  twitterImageAlt: 'Preview of My Amazing Site',
  ogType: 'website',
  ogUrl: 'https://myamazingsite.com', // Replace with your actual site URL
});
</script>
