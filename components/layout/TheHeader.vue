<template>
  <header>
    <!-- <div class="collapse" id="navbarToggleExternalContent">
        <div class="bg-dark p-4">
            <h5 class="text-white h4">Collapsed content</h5>
            <span class="text-muted">Toggleable via the navbar brand.</span>
        </div>
    </div> -->
    <div class="navbar navbar-dark bg-dark">
      <div class="headerBlock">
        <p>Цена</p>
        <span>от:</span>
        <input class="count" type="number" value="5" min="1" max="100000">
        <span>до:</span>
        <input class="count" type="number" value="5" min="1" max="100000">
      </div>
      <div class="headerBlock">
        <p>Сортировка</p>
        <div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1" checked>
                <label class="form-check-label" for="flexRadioDefault1">
                    По возрастанию цены
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2">
                <label class="form-check-label" for="flexRadioDefault2">
                    По убыванию цены
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault3">
                <label class="form-check-label" for="flexRadioDefault3">
                    По алфавиту
                </label>
            </div>
        </div>
      </div>
      <div class="headerBlock">
        <p>Валюта</p>
        <div class="input-group">
            <button class="btn btn-outline-secondary left" type="button">USD</button>
            <button class="btn btn-outline-secondary right" type="button">UAH</button>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'TheHeader'
}
</script>

<style>
header {
  width: 100%;
  margin-bottom: 15px;
}

.headerBlock {
  margin: 0 40px;
}

p {
  font-weight: bold;
}

.count {
  width: 90px;
}

.navbar {
  color: white;
  width: 100%;
  justify-content: center;
}

.left {
  border-radius: 20px 0 0 20px;
  color: white;
}

.right {
  border-radius: 0 20px 20px 0;
  color: white;
}
</style>
