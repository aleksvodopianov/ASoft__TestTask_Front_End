<template>
  <div>
    <ul class="list">
      <CardsListItem />
    </ul>
  </div>
</template>

<script>
import CardsListItem from '~/components/layout/CardsListItem'
export default {
  components: { CardsListItem }
}
</script>

<style>
.list {
  list-style: none;
  margin: 0;
  padding: 0;
  width: 700px;
}

.list-item {
  display: flex;
  background: #fff;
  height: 168px;
  margin-bottom: 15px;
  overflow: hidden;
  padding: 8px;
}

.list-item_content {
  padding: 0 10px 0 10px;
  width: calc(100% - 216px);
}

.list-item_header {
  display: flex;
  justify-content: space-between;
  width: 100%;
  height: 86%;
}

a {
  color: black;
}

.list-item-image {
  width: 216px;
  height: 152px;
  overflow: hidden;
}

img {
  height: 100%;
}
</style>
