<template>
  <vue-tiny-slider v-bind="tinySliderOptions" class="">
    <div class="h-screen flex">
      <div class="relative flex-initial h-3/4 bg-black-calima">
        <img class="absolute inset-x-0 bottom-0 " src="https://media.discordapp.net/attachments/334860109199048726/905246132605698048/9289a51f83f74ad902dde095ed73d01e.png" alt="Calima logo">
      </div>
      <div class="h-1/4 flex-initial     ">
        <img class="h-10 ml-5" src="https://cdn.discordapp.com/attachments/334860109199048726/905230787555766312/unknown.png" alt="Software Teams Remote.">
        <div class="relative flex-col top-2/3    ">
          <p class="  text-3xl 3xl:text-5xl font-bold absolute bottom-20  right-5 h-full  ">
            <span class=" bg-yellow-calima">Soul in Gran Canaria </span>
          </p>
          <p class=" text-3xl 3xl:text-5xl font-bold absolute bottom-6 3xl:bottom-2 right-5 h-full">
            <span class=" bg-yellow-calima  ">Heart in Berlin</span>
          </p>
        </div>
      </div>
    </div>
    <div class="">
      <div class="flex-col h-screen w-screen">
        <h1 class="text-8xl w-5/6  mx-auto flex">Project Summary <span class="text-9xl font-extrabold text-yellow-calima">_</span> </h1>
          <ul class="flex-col mt-24 list-disc w-5/4 mx-auto">
            <li class=" w-4/6 justify-center mx-auto text-2xl"><span class="text-7xl ">Quab</span></li>
          </ul>
      </div>
      <div class="flex w-full relative">
        <img class="absolute h-10 bottom-5 right-5" src="https://media.discordapp.net/attachments/334860109199048726/905879965973774336/unknown.png" alt="Calima logo black">
      </div>

    </div>
    <div>
      <div class="h-screen w-screen">
        <h1 class="text-8xl w-5/6  mx-auto flex">Quab<span class="text-9xl font-extrabold text-yellow-calima">_</span> </h1>
        <div class="flex-col items-center justify-center w-full">
          <img class="flex  justify-center items-center mx-auto" src="https://i.gyazo.com/05f628fd305cfa051b939974280ab6d7.png" alt="Quab template">
          <div class="flex items-center justify-center mt-20 w-full mx-auto">

        </div>
      </div>
    </div>
      <div class="flex w-full relative">
        <img class="absolute h-10 bottom-5 right-5" src="https://media.discordapp.net/attachments/334860109199048726/905879965973774336/unknown.png" alt="Calima logo black">
      </div>
    </div>
    <div class="h-screen flex ">
      <div class="relative flex-initial h-3/4 flex-row ">
        <img class="absolute  left-10 bottom-6" src="https://i.gyazo.com/3dd5578adb586d444fe000322a0d003a.png" alt="Software Teams Remote.">
      </div>
      <div class="h-1/4 flex-initial relative  bg-black-calima  ">
        <img class="h-20 absolute  left-10 bottom-6" src="https://media.discordapp.net/attachments/334860109199048726/905246132605698048/9289a51f83f74ad902dde095ed73d01e.png" alt="Software Teams Remote.">
        <div class="relative flex-col top-2/3    ">
          <p class="  text-3xl 3xl:text-5xl font-bold absolute bottom-12  right-5 h-full  ">
            <span class=" bg-yellow-calima">Soul in Gran Canaria </span>
          </p>
          <p class=" text-3xl 3xl:text-5xl font-bold absolute -bottom-2 3xl:bottom-2 right-5 h-full">
            <span class=" bg-yellow-calima  ">Heart in Berlin</span>
          </p>
        </div>
      </div>
    </div>
  </vue-tiny-slider>
</template>

<script>
export default {
  data () {
    return {
      tinySliderOptions: {
        mouseDrag: true,
        loop: true,
        items: 1,
        swipeAngle: 45,
        arrowKeys: true,
        controls: false,
        nav: false
      }
    }
  },
  head () {
    return {
      link: [
        {
          rel: 'stylesheet',
          href:
            'https://cdnjs.cloudflare.com/ajax/libs/tiny-slider/2.9.1/tiny-slider.css'
        }
      ]
    }
  }
}
</script>

<style>
</style>
