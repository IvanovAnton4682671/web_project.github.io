<template>
  <div class = "container-fluid ots" style = "margin-top: 2500px">
    <div class = "text-center">
      <h1>С нами работают</h1>
      <p class = "text-center">Десятки компаний доверяют нам самое ценное, что у них есть в интренете - свои сайты.</p>
      <p class = "text-center">Мы делаем всё, чтобы наше сотрудничество было долгим.</p>
    </div>
    <div id = "slide" style = "margin-left: 15px">
      <img src = "../assets/img/rings/1.jpg" class = "slide-single" alt = "ring1">
      <img src = "../assets/img/rings/2.jpg" class = "slide-single" alt = "ring2">
      <img src = "../assets/img/rings/3.jpeg" class = "slide-single" alt = "ring3">
      <img src = "../assets/img/rings/4.jpg" class = "slide-single" alt = "ring4">
      <img src = "../assets/img/rings/5.png" class = "slide-single" alt = "ring5">
    </div>
    <div id = "slide2" style = "margin-top: 20px">
      <img src = "../assets/img/rings/6.png" class = "slide-single2" alt = "ring6">
      <img src = "../assets/img/rings/7.png" class = "slide-single2" alt = "ring7">
      <img src = "../assets/img/rings/8.jpg" class = "slide-single2" alt = "ring8">
      <img src = "../assets/img/rings/9.jpg" class = "slide-single2" alt = "ring9">
      <img src = "../assets/img/rings/10.png" class = "slide-single2" alt = "ring10">
      <img src = "../assets/img/rings/11.png" class = "slide-single2" alt = "ring11">
    </div>
  </div>
</template>

<script>
  export default {
    name: "RingsApp"
  }
    /*let slides = document.querySelectorAll('.slide-single');
    console.log(slides);
    let slider = [];
    for (let i = 0; i < slides.length; i++) {
      slider[i] = slides[i].src;
      slides[i].remove();
    }
    console.log(slider);
    let step = 0;
    let offset = 0;

    function draw() {
      let img = document.createElement('img');
      img.src = slider[step];
      img.classList.add('slide-single');
      img.style.left = offset * 350 + 'px';
      document.querySelector('#slide').appendChild(img);
      if (step + 1 == slider.length)
        step = 0;
      else step++;
      offset = 1;
    }

    function left() {
      let slides2 = document.querySelectorAll('.slide-single');
      let offset2 = 2;
      for (let i = 0; i < slides2.length; i++) {
        slides2[i].style.left = offset2 * 350 - 350 + 'px';
        offset2++;
      }
      setTimeout(function () {
        slides2[0].remove();
        draw();
      }, 0);
    }

    document.onclick = left;*/
</script>

<style scoped>

.slide-single
{
  width: 350px;
  height: 150px;
  border: 1px solid #c4c4c4;
  margin-left: 3px;
  margin-right: 3px;
}

.slide-single2
{
  width: 295px;
  height: 150px;
  border: 1px solid #c4c4c4;
  margin-left: 3px;
  margin-right: 3px;
}
</style>