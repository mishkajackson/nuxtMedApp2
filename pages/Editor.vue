<template>
<div>
  <transition>
  <Editor/>
  </transition>
</div>


</template>

<script>
export default {
  transition: 'PsystatusSyndrome'
}
</script>

<style>
 .home-enter-active, .home-leave-active { transition: opacity .5s; }
  .home-enter, .home-leave-active { opacity: 0; }
</style>
