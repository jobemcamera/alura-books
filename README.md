# Curso Mobile First da Alura

## Alura Books


Neste curso, pude aprimorar minhas habilidades em criar uma página responsiva começando pela versão mobile.

## Versão Mobile (428px)

![image](https://user-images.githubusercontent.com/109925623/212206603-a9b73e3c-6eaa-4612-b6b0-475ad9fc00d6.png)


## Versão Tablet (1024px)

![image](https://user-images.githubusercontent.com/109925623/212207495-6262afc0-fe23-470c-b630-ebf2198058c1.png)


## Versão Desktop (1728px)

![image](https://user-images.githubusercontent.com/109925623/212206478-910e64ee-e3ba-480e-bb03-65857d824257.png)


## O que eu aprendi

Nesse projeto puder aprender como fazer um carrossel de itens, no caso, um slide de imagens, através do Swiper API.

Marcação do HTML

``` html

<section class="carrossel">
        <h2 class="carrossel__titulo">Mais Vendidos</h2>
        <!-- CARROSSEL -->
        <div class="carrossel__container">   
            <div class="swiper">
                <!-- Additional required wrapper -->
                <div class="swiper-pagination"></div>
                <div class="swiper-wrapper">
                <!-- Slides -->
                <div class="swiper-slide"><img src="assets/img/Nodejs.svg" alt="Livro NodeJS"></div>
                <div class="swiper-slide"><img src="assets/img/Gestão.svg" alt="Livro Gestão"></div>
                <div class="swiper-slide"><img src="assets/img/UX.svg" alt="Livro UX"></div>
                <div class="swiper-slide"><img src="assets/img/Gestão2.svg" alt="Livro Gestão"></div>
                <div class="swiper-slide"><img src="assets/img/Tuning.svg" alt="Livro Tuning"></div>
                </div>
                <!-- If we need navigation buttons -->
                <div class="swiper-button-prev"></div>
                <div class="swiper-button-next"></div>
            </div>
</setion>

```


Script JS

``` html
  <script src="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>
    <script>
        const swiper = new Swiper('.swiper', {
            spaceBetween: 0,
            slidesPerView: 2,
            pagination: {
                el: '.swiper-pagination',
                type: 'bullets',
            },
        });

   </script>
```
