<template>
  <div class = "container-fluid pt-3 pb-5 pb-md-0 footer_region" id = "FooterApp">
    <div class = "footer_background"></div>
    <div class = "row d-flex mt-2 px-2">
      <div class = "col-11 col-md-10 mx-auto px-0">
        <div class = "row">
          <div class = "col-11 col-md-5 mx-auto">
            <h1>Оставить заявку на поддержку сайта</h1>
            <p class = "col-10 text_">
              Срочно нужна поддержка сайта? Ваша команда не успевает справиться самостоятельно или предыдущий подрядчик не справился с работой?
              Тогда вам точно к нам! Просто оставьте заявку и наш менеджер с вами свяжется!
            </p>
            <div class = "text-start">
              <a class = "text-light text-decoration-none phone" href = "">8 800 222-26-73</a>
            </div>
            <div class = "text-start">
              <a class = "text-light email" href = "">info@drupal-coder.ru</a>
            </div>
          </div>
          <div class = "col-11 col-md-5 mx-auto">
            <form id = "Form" action = "https://formcarry.com/s/cFkX6p8Wc" method = "POST" enctype = "multipart/form-data" accept-charset = "UTF-8">
              <div class = "form-row" style = "margin-left: 4em ">
                <div class = "col-12">
                  <label class = "text-light form-group"><br/>
                    <input class = "form-control form-control-md info" type = "text" id = "Name" name = "lastName" placeholder = "Ваше имя" autocomplete = "off">
                  </label><br/>
                </div>
                <div class = "col-12">
                  <label class = "text-light form-group"><br/>
                    <input class = "form-control form-control-md info" type = "text" id = "Phone" name = "userPhone" placeholder = "Телефон" autocomplete = "off">
                  </label><br/>
                </div>
                <div class = "col-12">
                  <label class = "text-light form-group"><br/>
                    <input class = "form-control form-control-md info" type = "email" id = "Email" name = "userEmail" placeholder = "E-mail" autocomplete = "off">
                  </label><br/>
                </div>
                <div class = "col-12">
                  <label class = "form-group"><br/>
                    <textarea class = "form-control form-control-md info" name = "userMsg" id = "Text" placeholder = "Ваш комментарий" autocomplete = "off"></textarea>
                  </label><br/>
                </div>
                <div class = "col-12">
                  <label class = "text-light form-group">
                    <input type = "checkbox" id = "CB" name = "Agreement" class = "info">
                    Отправляя заявку, я даю согласие на
                    <a class = "form-politics" href = "" rel = "nofollow">обработку своих персональных данных. *</a>
                  </label><br/>
                </div>
                <div class = "col-12 mt-3">
                  <button class = "btn btn-footer" type="submit" id = "Button" >Свяжитесь с нами!</button>
                </div>
              </div>
            </form>
          </div>
        </div>
        <div class="col-12 footer+">
          <div class="row">
            <div class="col-md-6 col-12">
              <div class="row">
                <div class="emblems-block">
                  <ul class="emblems-list">
                    <li class="emblems-list-item">
                      <a href="#"><img src="../assets/img/facebook.svg" alt=""/></a>
                    </li>
                    <li class="emblems-list-item">
                      <a href="#"><img src="../assets/img/vk.svg" alt="" /> </a>
                    </li>
                    <li class="emblems-list-item">
                      <a href="#"
                      ><img src="../assets/img/youtube.svg" alt=""
                      /></a>
                    </li>
                    <li class="emblems-list-item">
                      <a href="#"><img src="../assets/img/telegram.svg" alt=""/></a>
                    </li>
                  </ul>
                  <div class="footerText">
                    <p>
                      Проект ООО «Инитлаб», Краснодар, Россия.<br />
                      Drupal является зарегистрированной торговой маркой Dries Buytaert.
                    </p>
                  </div>
                </div>
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
  name: "FooterApp"
}
</script>

<style scoped>

h1
{
  color: #e5e5e5;
  margin-bottom: 1em;
}

.text_
{
  color: #e5e5e5;
  margin-bottom: 5em;
}
.footer_region
{
  position: relative;
  width: 100%;
  height: auto;
  background: url("../assets/img/druplar-emblem.svg") top center,
  url("../assets/img/druplar-emblem2.png") bottom right;
  background-repeat: no-repeat;
}

.footer_background
{
  position: absolute;
  z-index: -2;
  background: linear-gradient(254.72deg, rgba(245, 240, 240, 0.27) -114.85%, rgba(252, 249, 249, 0) 69.04%), #06091c;
  left:0;
  right:0;
  top:0;
  bottom:0;
}

.emblems-block{
  margin: 40px;
}
.emblems-list-item {
  display: inline-block;
  margin-right: 10px;
}
.form-politics
{
  color: #ef4c35;
}

.btn-footer
{
  display: inline-block;
  color: white;
  text-decoration: none;
  padding: 1em 2em;
  outline: none;
  border-width: 2px 0;
  border-style: solid none;
  border-radius: 6px;
  background: #ef4c35;
  transition: 0.2s;
  width: 100%;
}

.phone, .email
{
  font-size:25px;
}

.form-group
{
  width: 100%;
}

.info
{
  background: transparent;
}
.emblems-list {
  list-style: none;
  display: flex;
  padding-left: 0;
}
.emblems-list-item a {
  width: 30px;
  height: 30px;
  background: #f14d34;
  display: inline-block;
  text-align: center;
  border-radius: 5px;
}
.emblems-list-item img {
  width: 18px;
  height: 16px;
  filter: invert(1);
}
.footerText {
  font-weight: normal;
  font-size: 14px;
  line-height: 17px;
  color: #ffffff;
  opacity: 0.5;
}
</style>