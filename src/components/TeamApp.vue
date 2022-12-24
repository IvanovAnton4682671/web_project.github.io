<template>
  <div class = "competency-region container-fluid">
    <div class = "competencies">
      <div class = "container">
        <div class = "row">
          <div class = "team">
            <h2 class = "competency-title">Команда</h2>
          </div>
        </div>
        <div class = "row competencies-row row-flex">
          <div class = "col-6 col-sm-4">
            <div class = "competency mb-3">
              <div class = "competency-wrapper">
                <div class = "competency-header">
                  <div class = "competency-icon">
                    <img src = "../assets/img/IMG_2472_0.jpg" alt = "IMG_2472_0" class = "img-responsive"/>
                  </div>
                </div>
                <h1>Сергей Синица</h1>
                <div class = "competency-body col-sm-8">Руководитель отдела веб-разработки, канд. тех. наук, заместитель директора</div>
              </div>
            </div>
          </div>
          <div class = "col-6 col-sm-4">
            <div class = "competency mb-3">
              <div class = "competency-wrapper">
                <div class = "competency-header">
                  <div class = "competency-icon">
                    <img src = "../assets/img/IMG_2539_0.jpg" alt = "IMG_2539_0" class = "img-responsive"/>
                  </div>
                </div>
                <h1>Роман Агабеков</h1>
                <div class = "competency-body col-sm-8">Руководитель отдела DevOPS, директор</div>
              </div>
            </div>
          </div>
          <div class = "col-6 col-sm-4">
            <div class = "competency mb-3">
              <div class = "competency-wrapper">
                <div class = "competency-header">
                  <div class = "competency-icon">
                    <img src = "../assets/img/IMG_2474_1.jpg" alt = "IMG_2474_1" class = "img-responsive"/>
                  </div>
                </div>
                <h1>Алексей Синица</h1>
                <div class = "competency-body col-sm-8">Руководитель отдела поддержки сайтов</div>
              </div>
            </div>
          </div>
          <div class = "col-6 col-sm-4">
            <div class = "competency mb-3">
              <div class = "competency-wrapper">
                <div class = "competency-header">
                  <div class = "competency-icon">
                    <img src = "../assets/img/IMG_2522_0.jpg" alt = "IMG_2522_0" class = "img-responsive"/>
                  </div>
                </div>
                <h1>Дарья Бочкарёва</h1>
                <div class = "competency-body col-sm-8">Руководитель отдела продвижения, контекстной рекламы и контент-поддержки сайтов</div>
              </div>
            </div>
          </div>
          <div class = "col-6 col-sm-4">
            <div class = "competency mb-3">
              <div class = "competency-wrapper">
                <div class = "competency-header">
                  <div class = "competency-icon">
                    <img src = "../assets/img/IMG_9971_16.jpg" alt = "IMG_9971_16" class = "img-responsive"/>
                  </div>
                </div>
                <h1>Ирина Торкунова</h1>
                <div class = "competency-body col-sm-7">Менеджер по работе с клиентами</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class = "price-footer text-center mt-2">
      <a href = "#FooterApp" role = "button" class = "btn btn-outline-light btn-price button_team">вся команда</a>
    </div>
  </div>
</template>

<script>
  export default
  {
    name: 'TeamApp'
  }
</script>

<style scoped>

  h1
  {
    margin-top: 20px;
    font-size: 20px;
  }

  .button_team
  {
    color: #292b2c;
    border-color: #292b2c;
    width: 20%;
    margin-bottom: 50px;
  }

  .team
  {
    text-align: center;
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