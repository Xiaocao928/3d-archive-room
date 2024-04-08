<template>
  <div>
    <MainHeader />
    <MainSide />
    <MainScene />
  </div>
</template>

<script>
import MainHeader from '@/components/MainHeader.vue';
import MainSide from '@/components/MainSide.vue';
import MainScene from '@/components/MainScene.vue';

export default {
  name: 'archiveRoom',
  components: {
    MainHeader,
    MainSide,
    MainScene,
  },
  data() {
    return {};
  },
};
</script>

<style>

</style>
