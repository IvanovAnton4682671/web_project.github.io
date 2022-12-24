<template>
  <div class = "competency-region container-fluid">
    <div class = "competencies">
      <div class = "container">
        <div class = "row">
          <div class = "col-md-10 time">
            <h1 class = "competency-title">Наши профессиональные разработчики выполняют быстро любые задачи</h1>
          </div>
        </div>
        <div class = "row competencies-row row-flex">
          <div class = "col-6 col-sm-3">
            <div class = "competency mb-3">
              <div class = "competency-wrapper">
                <div class = "competency-header">
                  <div class = "competency-icon">
                    <img src = "../assets/img/competency-20.svg" alt = "competency-20" class = "img-responsive"/>
                  </div>
                </div>
                <h1>от 1ч</h1>
                <div class = "competency-body">Настройка события GA в интернет-магазине</div>
              </div>
            </div>
          </div>
          <div class = "col-6 col-sm-3">
            <div class = "competency mb-3">
              <div class = "competency-wrapper">
                <div class = "competency-header">
                  <div class = "competency-icon">
                    <img src = "../assets/img/competency-21.svg" alt = "competency-21" class = "img-responsive"/>
                  </div>
                </div>
                <h1>от 20ч</h1>
                <div class = "competency-body">Разработка мобильной версии сайта</div>
              </div>
            </div>
          </div>
          <div class = "col-6 col-sm-3">
            <div class = "competency mb-3">
              <div class = "competency-wrapper">
                <div class = "competency-header">
                  <div class = "competency-icon">
                    <img src = "../assets/img/competency-22.svg" alt = "competency-22" class = "img-responsive"/>
                  </div>
                </div>
                <h1>от 8ч</h1>
                <div class = "competency-body">Интеграция модуля оплаты</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default
  {
    name: 'TimeApp'
  }
</script>

<style scoped>

  .time
  {
    margin-bottom: 50px;
  }

  @media (max-width: 1300px)
  {
    .container
    {
      position: relative;
      z-index: 15;
    }
  }

  .competencies
  {
    padding: 150px 0;
  }

  .competency-title
  {
    font-size: 42px;
    font-weight: 1000;
    margin-bottom: 20px;
  }

  .competency-body
  {
    font-size: 15px;
    margin-top: 20px;
  }
</style>