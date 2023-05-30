<template>
    <div>
      <div class="bg-trading-tools relative max-w-full sm:mx-4 xl:mx-10 my-24 shadow sm:rounded-2xl overflow-hidden">
      <BaseSection>
        <div class="col-span-12 lg:col-span-6 mt-12 xl:mt-10 space-y-4 sm:space-y-6 px-6 text-center sm:text-left">
          <h1
            data-aos="fade-right"
            data-aos-once="true"
            class="text-[2.5rem] sm:text-5xl xl:text-6xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10"
          >
          <span class="text-header-gradient">Egzamin Zawodowy EE.14</span>
          </h1>
          <p data-aos="fade-down" data-aos-once="true" data-aos-delay="300" class="paragraph hidden sm:block">
            Arkusz E.14-11-19.01 Rok 2019 <br class="hidden sm:block" /> 
          </p>
          <div
            data-aos="fade-up"
            data-aos-once="true"
            data-aos-delay="700"
            class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4 mt-2"
          >
          </div>
        </div>
        <div class="hidden sm:block col-span-12 lg:col-span-6">
          <div class="w-full">
            <img
              data-aos="fade-up"
              data-aos-once="true"
              :src="require('~/assets/img/heo.webp')"
              class="-mt-4"
              alt=""
            />
          </div>
        </div>
        <img
          data-aos="fade-up"
          data-aos-delay="300"
          :src="require('~/assets/img/pattern/ellipse-1.png')"
          class="hidden sm:block absolute bottom-12 xl:bottom-16 left-4 xl:left-0 w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="300"
          :src="require('~/assets/img/pattern/ellipse-2.png')"
          class="hidden sm:block absolute top-4 sm:top-10 right-64 sm:right-96 xl:right-[32rem] w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="300"
          :src="require('~/assets/img/pattern/ellipse-3.png')"
          class="hidden sm:block absolute bottom-56 right-24 w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="300"
          :src="require('~/assets/img/pattern/star.png')"
          class="hidden sm:block absolute top-20 sm:top-28 right-16 lg:right-0 lg:left-[30rem] w-8"
        />
      </BaseSection>

        <iframe src="https://blankiwrld.github.io/inf03-iframe/index.html" style="border:0px #ffffff none;" name="stronka" scrolling="yes" frameborder="1" marginheight="0px" marginwidth="0px" height="850px" width="1900px" allowfullscreen></iframe>
      </div>
      <div>
        <div class="text-center">
          <h2 class="text-4xl font-semibold text-neutral-900 mb-4">Zadanie 1</h2>
          <p class="text-lg text-neutral-700 px-4 text-left ">Do pierwszego zadania będziemy potrzebować paru umiejętności korzystania z filtrów w Gimpie. Pierwszym zadaniem jest przeskalowanie zdjęć na mniejsze oraz dodanie filtrów zniekształcenia. Wszystkie zdjęcia znajdują się w folderze <code>materialy-5-6.zip</code> na pulpicie. Folder jest zabezpieczony hasłemn <code>Zdj3ci@</code></p>
          <h3> Krótki poradnik Gimpa</h3>
         <!-- make centered iframe -->
            <div class="flex justify-center">
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/K10oh31rnQI?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <h2 class="text-4xl font-semibold text-neutral-900 mb-4">Zadanie 2</h2>
          <p class="text-lg text-neutral-700 px-4 text-left ">Tworzymy plik index.html, psy.html, koty.html, index.js, style5.css </p>
          <h3> Poszczególne pliki mają wyglądać tak:</h3>
          <div class="flex justify-center">
            <blockquote class="imgur-embed-pub" lang="en" data-id="a/DVkt20f" data-context="false" ><a href="//imgur.com/a/DVkt20f"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
            </div>
      </div>
    </div>
    </div>
  </template>
  
  <script>
  import aosMixin from '@/mixins/aos'
  
  export default {
    mixins: [aosMixin],
  }
  </script>
  