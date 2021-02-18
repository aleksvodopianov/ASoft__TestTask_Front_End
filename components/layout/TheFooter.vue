<template>
  <footer>
    <nav class="navbar-dark bg-dark footerNav">
      <div class="footer__left-block">
        <div class="footer__name">
          <p>Имя</p>
          <input type="text" placeholder="Name">
        </div>
        <div class="footer__price">
          <p>Цена</p>
          <input type="number" value="5" min="1" max="100000">
        </div>
        <div class="footer__add-image">
          <p>Изображение</p>
          <input type="button" value="+">
        </div>
      </div>
      <div class="footer__right-block">
        <div class="form-floating">
          <textarea class="form-control" placeholder="Description"></textarea>
        </div>
        <div>
          <input type="button" value="Save" class="footer__save-btn">
        </div>
      </div>
    </nav>
  </footer>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>

<style>
.footerNav {
  padding: 20px 0 80px 0;
  display: flex;
  justify-content: center;
  color: #fff;
}

.footer__left-block {
  width: 280px;
  height: 170px;
  display: flex;
  flex-direction: column;
  margin: 0 20px;
}

.footer__right-block {
  height: 170px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin: 0 20px;
}

.footer__name {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
}

.footer__price {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
}

.footer__add-image {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
}

textarea.form-control {
  height: 79px;
}

.footer__save-btn {
  width: 232px;
  height: 35px;
}
</style>
