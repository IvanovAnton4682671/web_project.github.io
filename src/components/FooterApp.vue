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
            <form id = "Form" action = "https://formcarry.com/s/LKEmd9SHK" method = "POST" enctype = "multipart/form-data" accept-charset = "UTF-8">
              <div class = "form-row">
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
                  <input type = "button" class = "btn btn-footer btn-warning btn-lg btn-block" id = "Button" value = "Свяжитесь с нами!">
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
  export default
  {
    name: "FooterApp"
  }

  /*function Send() {
    var json = '{"key": "Форма была отправлена"}';
    var obj = JSON.parse(json);
    alert(obj.key);
    var xhr = new XMLHttpRequest();
    function go() {
      xhr.open('GET', '/project/form/a.txt', false);
      xhr.send();
      var element = document.getElementById('frag');
      element.innerHTML = xhr.responseText;
      return false;
    }
  }

  let u_name = document.getElementById('Name');
  let u_phone = document.getElementById('Phone');
  let u_email = document.getElementById('Email');
  let u_message = document.getElementById('Text');
  let u_cb = document.getElementById('CB');

  function save() {
    localStorage.setItem('Имя', u_name.value);
    localStorage.setItem('Телефон', u_phone.value);
    localStorage.setItem('Почта', u_email.value);
    localStorage.setItem('Сообщение', u_message.value);
    if (u_cb.checked) {
      localStorage.setItem('Чекбокс', 1);
    }
    else {
      localStorage.setItem('Чекбокс', 0);
    }
  }

  document.addEventListener('DOMContentLoaded', () => {
    u_name.value = localStorage.getItem('Имя');
    u_phone.value = localStorage.getItem('Телефон');
    u_email.value = localStorage.getItem('Почта');
    u_message.value = localStorage.getItem('Сообщение');
    let checkBox = localStorage.getItem('Чекбокс');
    if (checkBox == 1) {
      u_cb.checked = true;
    }
    else if (checkBox == 0) {
      u_cb.checked = false;
    }

    u_name.oninput = save;
    u_phone.oninput = save;
    u_email.oninput = save;
    u_message.oninput = save;
    u_cb.oninput = save;

    window.onpopstate = function () {
      window.history.back();
    };
    history.pushState({page: 1}, 'Form', '?Form');

    $(function () {
      $('#Form').submit(function (e) {
        e.preventDefault();
        $.ajax({
          type: 'POST',
          dataType: 'json',
          url: 'https://formcarry.com/s/LKEmd9SHK',
          data: $(this).serialsize(),
          success: function (response) {
            if (response.status == 'success') {
              alert('Форма была отправлена!');
              localStorage.removeItem('Имя');
              localStorage.removeItem('Телефон');
              localStorage.removeItem('Почта');
              localStorage.removeItem('Сообщение');
              localStorage.removeItem('Чекбокс');
              u_name.value = localStorage.getItem('Имя');
              u_phone.valus = localStorage.getItem('Телефон');
              u_email.value = localStorage.getItem('Почта');
              u_message.value = localStorage.getItem('Сообщение');
              u_cb.checked = false;
            }
          },
          error: function (jqxhr, status, errorMsg) {
            alert('Ошибка!');
          },
        });
      });
    });
  });*/
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
  }

  .footer_background
  {
    position: absolute;
    z-index: -2;
    background: linear-gradient(254.72deg,rgba(255,255,255,.276) -114.85%,rgba(255,255,255,0) 69.04%),#040613;
    left:0;
    right:0;
    top:0;
    bottom:0;
  }

  .form-politics
  {
    color: #e52d3b;
  }

  .btn-footer
  {
    color: white;
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
</style>