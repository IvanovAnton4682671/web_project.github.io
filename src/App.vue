<!--
<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
-->

<template>
  <head>
    <meta charset = "utf-8">
    <meta name = "viewport" content = "width = device-width, initial-scale = 1, shrink-to-fit = no">
    <link rel = "stylesheet" href = "master/bootstrap/css/bootstrap.min.css">
    <link rel = "stylesheet" type = "text/css" href= "master/slick/slick.css">
    <link rel = "stylesheet" type = "text/css" href= "master/slick/slick-theme.css">
    <!--<link rel = "stylesheet" href = "master/css/style.css">-->
    <link href = 'http://fonts.googleapis.com/css?family=Montserrat' rel = 'stylesheet' type = 'text/css'>
    <title>Проект</title>
  </head>
  <body>
    <header class = "navbar_main">
      <div class = "header_background">
        <video autoplay muted loop class = "video_background">
          <source src = "master/video/video.mp4" type = "video/mp4">
        </video>
      </div>
      <div class = "navbar navbar-expand-lg navbar-dark pt-4" id = "nav_bar">
        <div class = "container-fluid px-2 px-lg-0">
          <div class = "ms-0 ms-lg-4">
            <a class = "navbar_logo" href = "#">
              <img class = "img-fluid" src = "master/img/drupal-coder.svg" alt = "Project" width = "150" height = "30">
            </a>
          </div>
          <button class = "navbar-toggler" type = "button" data-toggle = "collapse" data-target = "#navbarToggler" aria-controls = "navbarToggler" aria-expanded = "false" aria-label = "Toggle navigation">
            <span class = "navbar-toggler-icon"></span>
          </button>
          <div class = "collapse navbar-collapse justify-content-center" id = "navbarToggler">
            <ul class = "navbar-nav">
              <li class = "nav-item">
                <a class = "nav-link active text-light navbar-effect" aria-current = "page" href = "">ПОДДЕРЖКА DRUPAL</a>
              </li>
              <li class = "nav-item dropdown" onmouseover = "showDropdown('#navbarDropdown-1', '#list-1')" onmouseout = "hideDropdown('#navbarDropdown-1','#list-1')">
                <a class = "nav-link dropdown-toggle text-light" href = "#" id = "navbarDropdown1" role = "button" data-toggle = "dropdown" aria-expanded = "false">АДМИНИСТРИРОВАНИЕ</a>
                <ul id = "list-1" class = "dropdown-menu dropdown-menu-dark" aria-labelledby = "navbarDropdown-1">
                  <li><a class = "dropdown-item text-light" href = "#">МИГРАЦИЯ</a></li>
                  <li><a class = "dropdown-item text-light" href = "#">БЭКАПЫ</a></li>
                  <li><a class = "dropdown-item text-light" href = "#">АУДИТ БЕЗОПАСНОСТИ</a></li>
                  <li><a class = "dropdown-item text-light" href = "#">ОПТИМИЗАЦИЯ СКОРОСТИ</a></li>
                  <li><a class = "dropdown-item text-light" href = "#">ПЕРЕЕЗД НА HTTPS</a></li>
                </ul>
              </li>
              <li class = "nav-item">
                <a class = "nav-link text-light" href = "#">ПРОДВИЖЕНИЕ</a>
              </li>
              <li class = "nav-item">
                <a class = "nav-link text-light" href = "#">РЕКЛАМА</a>
              </li>
              <li class = "nav-item dropdown" onmouseover = "showDropdown('#navbarDropdown-2','#list-2')" onmouseout = "hideDropdown('#navbarDropdown-2','#list-2')">
                <a class = "nav-link dropdown-toggle text-light" href = "#" id = "navbarDropdown-2" role = "button" data-toggle = "dropdown" aria-expanded = "false">О НАС</a>
                <ul id = "list-2" class = "dropdown-menu dropdown-menu-dark" aria-labelledby = "navbarDropdown-2">
                  <li><a class = "dropdown-item text-light" href = "#team">КОМАНДА</a></li>
                  <li><a class = "dropdown-item text-light" href = "#blogger">DRUPALGIVE</a></li>
                  <li><a class = "dropdown-item text-light" href = "#blogger">БЛОГ</a></li>
                  <li><a class = "dropdown-item text-light" href = "#">ВАКАНСИИ</a></li>
                  <li><a class = "dropdown-item text-light" href = "#">КУРСЫ DRUPAL</a></li>
                </ul>
              </li>
              <li class = "nav-item">
                <a class = "nav-link text-light" href = "#">ПРОЕКТЫ</a>
              </li>
              <li class = "nav-item">
                <a class = "nav-link text-light" href = "#">КОНТАКТЫ</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <!--Тут закончил-->
    </header>
  </body>
</template>

<style>
  body
  {
    font-family: "Montserrat", sans-serif;
  }

  .dropdown-menu
  {
    background-color: #292b2c;
  }

  .header_background
  {
    position: absolute;
    z-index: -2;
    background-color: #040613;
    left: 0; right: 0; top: 0; bottom: 0;
  }

  .video_background
  {
    top: 50%;
    width: 100%;
    transform: translate(-50%, -50%);
    opacity: 0.15;
    filter: blur(2px);
    left: 50%;
    z-index: -1;
    position: absolute;
    height: auto;
  }
</style>