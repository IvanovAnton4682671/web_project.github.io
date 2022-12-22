<template>
  <div class="container-fluid pt-3 pb-5 pb-md-0 footer_region" id="footerRegion">
    <div class="footer_background"></div>
    <div class="row d-flex mt-2 px-2">
      <div class="col-11 col-md-10 mx-auto px-0">
        <div class="row">
          <div class="col-11 col-md-5 mx-auto">
            <h5 class="text-head-footer text-md-start text-xxl-center text-white">
              Оставить заявку на
              <br/>
              поддержку сайта
            </h5>
            <p class="text-extra-footer text-start text-white">
              Срочно нужна поддержка сайта? Ваша команда не успевает справиться самостоятельно или предыдущий подрядчик не справился с работой?
              Тогда вам точно к нам! Просто оставьте заявку и наш менеджер с вами свяжется!
            </p>
            <div class="text-start">
              <a class="text-light text-decoration-none phone" href="">
                8 800 222-26-73
              </a>
            </div>
            <div class="text-start">
              <a class="text-light email" href="">
                info@drupal-coder.ru
              </a>
            </div>
          </div>
          <div class="col-11 col-md-5 mx-auto">
            <form id="Form" action="https://formcarry.com/s/NHJ3ElLaq" method="POST" enctype="multipart/form-data" accept-charset="UTF-8">
              <div class="form-row">
                <div class="col-12">
                  <label class="text-light form-group"><br/>
                    <input class="form-control form-control-md info" type="text" name="lastName" placeholder="Ваше имя" autocomplete="off">
                  </label><br/>
                </div>
                <div class="col-12">
                  <label class="text-light form-group"><br/>
                    <input class="form-control form-control-md info" type="text" name="userPhone" placeholder="Телефон" autocomplete="off">
                  </label><br/>
                </div>
                <div class="col-12">
                  <label class="text-light form-group"><br/>
                    <input class="form-control form-control-md info" type="email" name="userEmail" placeholder="E-mail" autocomplete="off">
                  </label><br/>
                </div>
                <div class="col-12">
                  <label class="form-group"><br/>
                    <textarea class="form-control form-control-md info" name="userMsg" placeholder="Ваш комментарий" autocomplete="off"></textarea>
                  </label><br/>
                </div>
                <div class="col-12">
                  <label class="text-light form-group">
                    <input type="checkbox" id="check" class="info">
                    Отправляя заявку, я даю согласие на
                    <a class="form-politics" href="" rel="nofollow">
                      обработку своих персональных данных. *
                    </a>
                  </label><br/>
                </div>
                <div class="col-12 mt-3">
                  <input type="button" class="btn btn-footer btn-warning btn-lg btn-block" id="Button" value="Свяжитесь с нами!" disabled>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterApp"
}
</script>

<style scoped>
.footer_region{
  position: relative;
  width: 100%;
  height: auto;
}
.footer_background{
  position: absolute;
  z-index: -2;
  background: linear-gradient(254.72deg,rgba(255,255,255,.276) -114.85%,rgba(255,255,255,0) 69.04%),#040613;
  left:0;
  right:0;
  top:0;
  bottom:0;
}
.form-politics{
  color: #e52d3b;
}
.btn-footer{
  color: white;
}

.phone, .email{
  font-size:25px;
}
.form-group{
  width: 100%;
}
.info{
  background: transparent;
}

</style>