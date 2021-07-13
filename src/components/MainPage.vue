<template>
  <div class="test">
    <div class="row">
      <div class="col span-1-of-2">
        <img src="../img/карта2.png" alt="Iphone screen" class="app-screen">
      </div>
      <div class="col span-1-of-2">
        <div class="container">
          <div class="item">
            <div>100 дней без %</div>
            <p>на любые покупки</p>
          </div>
          <div class="item">
            <div>11,99%</div>
            <p>минимальная процентная ставка</p>
          </div>
          <div class="item">
            <div>500 000 ₽</div>
            <p>максимальный кредитный лимит</p>
          </div>
          <div class="item">
            <div>Бесплатная доставка</div>
            <p>доставим карту в удобное место и время</p>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>

export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


.row {
  max-width: 1000px;
  margin: 0 auto;
}


img {
  width: 80%;
}

.item {
  margin: 20px;

  width: 200px;
  height: 100px;
}

.container {
  display: grid;
  grid-template-columns: 50% 50%;
  margin: 40px 200px 0 0;
}

</style>
