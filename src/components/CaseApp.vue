<template>
  <div id="blogger" class="container blog my-4">
    <h1 class="text-center mb-5"> Последние кейсы</h1>
    <div class="row gy-4">
      <div class="blog-guts col-12 col-md-4">
        <div class="blog-body position-relative">
          <article>
            <a href="#">
              <div class="case-image">
                <img src="../assets/img/img_noyt1.jpg" class="img-fluid" alt="1"/>
              </div>
              <div class="header-date px-3 py-4">
                <h5> <b>Настройка кэширования данных. Апгрейд сервера. Ускорение работы сайта в 30 раз!</b> </h5>
                <div class="case-date">
                  <p> 04.05.2020 </p>
                </div>
                <div class="blog-desc mt-4">
                  <p> Влияние скорости загрузки страниц сайта на отказы и конверсии. Кейс ускорения... </p>
                </div>
              </div>
            </a>
          </article>
        </div>
      </div>
      <div class="blog-guts col-12 col-md-8">
        <article>
          <a href="#">
            <div class="case-body position-relative">
              <div class="case-image-internalized main-image">
                <img src="../assets/img/img_case2.jpg"  class="img-fluid" alt="2"/>
              </div>
              <div class="header-date header-date-internalized px-3 py-4">
                <h5><b> Использование отчетов Ecommerce в Яндекс.Метрике</b> </h5>
              </div>
            </div>
          </a>
        </article>
      </div>
      <div class="blog-guts col-12 col-md-4">
        <article>
          <a href="#">
            <div class="cringe position-relative">
              <div class="case-image-internalized">
                <img src="../assets/img/img_noyt2.png" class="img-fluid" alt="3" style = "filter: blur(1px)"/>
              </div>
              <div class="header-date header-date-internalized px-3">
                <h5><b> Повышение конверсии страницы с формой заявки с применением AB-тестирования
                  Повышение конверсии страницы с формой заявки с применением AB-тестирования</b> </h5>
                <div class="case-date">
                  <p> 24.01.2020 </p>
                </div>
              </div>
            </div>
          </a>
        </article>
      </div>
      <div class="blog-guts col-12 col-md-4">
        <article>
          <a href="#">
            <div class="cringe position-relative">
              <div class="case-image-internalized">
                <img src="../assets/img/img_case4.jpeg" class="img-fluid" alt="4" style = "filter: blur(1px)"/>
              </div>
              <div class="header-date header-date-internalized px-3">
                <h5><b> Drupal 7: ускорение времени генерации страниц интернет-магазина на 32% </b> </h5>
                <div class="case-date">
                  <p> 23.09.19 </p>
                </div>
              </div>
            </div>
          </a>
        </article>
      </div>
      <div class="blog-guts col-12 col-md-4">
        <article>
          <a href="#">
            <div class="position-relative">
              <div class="case-image">
                <img src="../assets/img/img_case5.png" class="img-fluid" alt="5">
              </div>
              <div class="header-date px-3 py-4">
                <h5> Обмен товарами и заказами интернет-магазинов на Drupal 7 с 1С: Предприятие, МойСклад, Класс365 </h5>
                <div class="case-date">
                  <p> 22.08.2019 </p>
                </div>
                <div class="blog-desc mt-4">
                  <p> Опубликован релиз модуля... </p>
                </div>
              </div>
            </div>
          </a>
        </article>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CaseApp"
}
</script>

<style scoped>
.price-text p{
  margin-bottom: 5px;
}
.blog{
  max-width: 960px;
  font-size: 16px;
}
.blog-guts{
  height: 360px;
  cursor: pointer;
}
.blog-guts a, a:hover, a:focus, a:active {
  text-decoration: none;
  color: inherit;
}
.blog-guts a:hover h5:hover{
  text-decoration: underline;
}
.blog-guts h5, .blog-guts p{
  font-size: 14px;
}
.case-image img{
  height: 140px;
  object-fit: cover;
  border-radius: 6px;

}
.case-image-internalized img{
  height: 3600px;
  object-fit: cover;
  border-radius: 8px;
}
.header-date-internalized{
  position:absolute;
  bottom:0;
  left:0;
  right:0;
  z-index: 1000;
}
.blog-desc p{
  color: black;
}
.header-date-internalized h5{
  color:white;
}
.case-date{
  color: lightgray;
}
@media screen and (min-width: 770px){
  .blog-guts{
    height: 470px;
  }
  .blog-guts h5, .blog-guts p{
    font-size: 18px;
  }
  .case-image-internalized img{
    height: 470px;
  }
  .case-image img{
    height: 200px;
  }
}
</style>