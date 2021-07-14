<template>
  <div>
    <div class="row">
      <div class="img-cont col span-1-of-2">
        <img src="../img/карта1.jpeg" alt="Изображение карты">
      </div>
      <div class="col span-1-of-2">
        <ul class="advantage-container">
          <li class="advantage-item">
            <div>100 дней без %</div>
            <div>на любые покупки</div>
          </li>
          <li class="advantage-item">
            <div>11,99%</div>
            <div>минимальная процентная ставка</div>
          </li>
          <li class="advantage-item">
            <div>500 000 ₽</div>
            <div>максимальный кредитный лимит</div>
          </li>
          <li class="advantage-item">
            <div>Бесплатная доставка</div>
            <div>доставим карту в удобное место и время</div>
          </li>
        </ul>
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
  width: 70%;
  margin-left: 10%;
}

.advantage-item {
  margin-left: 5px;
  width: calc(50% - 5px);
  height: 100px;
}

.advantage-item div {
  text-align: left;
}

.advantage-item div:first-child {
  font-weight: 600;
  font-size: 130%;
}

.advantage-item div:last-child {
  width: 80%;
}

.advantage-container {
  display: flex;
  flex-wrap: wrap;
  margin: 60px 0 0 0;
}

li {
  display: list-item;
  text-align: -webkit-match-parent;
  list-style-type: none;
}

ul {
  list-style-type: disc;
}

div {
  display: block;
}


</style>
