<template>
    <div class="main">
          <div class="main-inner">
      <div class="current-series"><h3>Current Series</h3></div>
      <div v-for="(comic, index) in comics" :key="index" class="comic-card">
        <div class="comic-cover">
          <img :src="comic.thumb" :alt="`Cover by ${comic.series}`" />
        </div>
        <span>{{ comic.series }}</span>
      </div>
    </div>
    <span class="more-comics">Load More</span>
    </div>
</template>

<script>
export default {
  props: {
    comics: Array,
  },
};
</script>

<style lang="scss" scoped>


.main {
  color: #fff;
  background-color: #333;
  padding: 20px 0 30px;
  text-align: center;

  .main-inner {
    width: 1200px;
    margin: 0 auto;
    margin-bottom: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    position: relative;

    .current-series {
      position: absolute;
      padding: 10px 20px;
      margin: -40px -10px;
      text-transform: uppercase;
      background-color: #0282f9;
    }

    .comic-card {
      width: calc((1200px / 6) - 20px);
      margin-top: 20px;
      display: flex;
      flex-direction: column;
      text-align: left;
      cursor: pointer;

      .comic-cover {
        width: 100%;
        height: calc((1200px / 6) - 20px);
        overflow: hidden;

        img {
          width: 100%;
        }
      }

      span {
        margin: 20px 0;
        text-transform: uppercase;
      }
    }
  }
  .more-comics {
    margin: 0 auto;
    padding: 10px 40px;
    background-color: #0282f9;
    cursor: pointer;
    text-transform: uppercase;
    font-weight: 900;
  }
}
</style>