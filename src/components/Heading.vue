<template>
  <div class="row hero">
    <picture class="hero__image">
      <source type="image/webp" srcset="../assets/profile@1x.webp 1x, ../assets/profile@2x.webp 2x, ../assets/profile@2x.webp 4x">
      <img src="../assets/profile@2x.jpg" alt="Siro profile picture" loading="lazy" width="135" height="180">
    </picture>
  </div>
</template>

<script>
export default {
  name: 'Heading'
}
</script>
