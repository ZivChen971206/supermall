<template>
  <div class="recommend-info">
    <div class="info-header">热门推荐</div>
    <goods-list-item
      v-for="(item, index) in recommendList"
      :key="index"
      :goods="item"
    ></goods-list-item>
  </div>
</template>

<script>
import GoodsListItem from "views/home/childComps/GoodsListItem";

export default {
  name: "DetailRecommendInfo",
  components: {
    GoodsListItem,
  },
  props: {
    recommendList: {
      type: Array,
    },
  },
};
</script>

<style scoped>
.recommend-info {
  padding: 5px;
}

.info-header {
  line-height: 40px;
  padding-left: 8px;
  font-size: 15px;
  color: #333;
}
</style>
