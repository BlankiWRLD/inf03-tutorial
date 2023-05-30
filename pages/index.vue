<template>
  <div class="w-full">
    <!-- Hero section -->
    <section id="hero" class="w-full pb-24">
      <BaseSection>
        <div class="col-span-12 lg:col-span-6 mt-12 xl:mt-10 space-y-4 sm:space-y-6 px-6 text-center sm:text-left">
          <h1
            data-aos="fade-right"
            data-aos-once="true"
            class="text-[2.5rem] sm:text-5xl xl:text-6xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10"
          >
          <span class="text-header-gradient">Egzamin Zawodowy INF.03</span>
          </h1>
          <p data-aos="fade-down" data-aos-once="true" data-aos-delay="300" class="paragraph hidden sm:block">
            Zobacz jak mało trzeba umieć aby zdać egzamin zawodowy 😋 <br class="hidden sm:block" /> 
          </p>
          <div
            data-aos="fade-up"
            data-aos-once="true"
            data-aos-delay="700"
            class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4 mt-2"
          >
            <BaseButton
              class="max-w-full px-8 py-4 bg-gradient-to-r from-[#468ef9] to-[#0c66ee] border border-[#0c66ee] text-white"
            >
            <span class="mr-2">
                <a href="/CodingTutorial">Pordanik</a>
              </span>
            </BaseButton>
            <BaseButton
              class="max-w-full px-6 py-4 bg-inherit text-gradient border border-[#0c66ee] flex items-center justify-center"
            >
              <!-- make link to download egzamin -->
              <span class="mr-2">
                <a href="https://arkusze.pl/egzamin-zawodowy-kwalifikacja-e-14/">Pobierz egzaminy</a>
              </span>
            
            <ChevronDownIcon :size="20" class="mt-1 text-[#0c66ee]" />
            </BaseButton>
          </div>
        </div>
        <div class="hidden sm:block col-span-12 lg:col-span-6">
          <div class="w-full">
            <img
              data-aos="fade-up"
              data-aos-once="true"
              :src="require('~/assets/img/hero-image.webp')"
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
    </section>
    <section
      class="max-w-screen-xl mx-2 sm:mx-auto px-4 sm:px-6 lg:px-0 py-6 pb-20 sm:py-8 rounded-[2.25rem] sm:rounded-xl bg-white shadow-lg sm:shadow-md transform lg:-translate-y-12"
      >

      <div class="py-8 sm:py-4 text-center  text-sm text-[#666666] hover:text-gray-900">
        Pobaw się kodem na typowej stronie egzaminacyjnej
    </div>
      <div class="w-full flex flex-col lg:flex-row items-center justify-center">
        <iframe height="500" style="width: 100%;" scrolling="no" title="Egzamin INF. 03" src="https://codepen.io/blankiwrld/embed/jOeoVBe?default-tab=html%2Cresult&editable=true&theme-id=dark" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/blankiwrld/pen/jOeoVBe">
  Egzamin INF. 03</a> by BlankiWRLD (<a href="https://codepen.io/blankiwrld">@blankiwrld</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>
      </div>
    </section>
   
    <section id="kursy" class="bg-trading-tools relative max-w-full sm:mx-4 my-20 py-16 shadow rounded-2xl overflow-hidden">
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-4xl font-semibold">Moje Źródła <span class="text-header-gradient">Wiedzy</span></h2>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">Udemy</h4>
            <p class="paragraph text-sm xl:text-base">
              Jak się chce to się może. Udemy to platforma z kursami online. Wystarczy wybrać kurs, zapłacić i zacząć
              oglądać. Ogółem polecam kurs <b>Kurs Web Developer Tworzenie Stron od zera do Mastera</b>. Jest ciągle aktualizowany
              oraz dzięki niemu dowiesz się więcej na temat web devu niż na studiach.
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">StackOverflow</h4>
            <p class="paragraph text-sm xl:text-base">
              Gdy masz problem z kodem, to StackOverflow jest najlepszym miejscem do znalezienia rozwiązania. Wystarczy
              wpisać w wyszukiwarce swój problem i gotowe. Jeśli nie ma rozwiązania, to możesz zadać pytanie i ktoś
              na pewno odpowie. (albo cię zwyzywa)
            </p>
          </div>
          <div class="space-y-2">
            <h4 class="text-lg font-medium">YouTube</h4>
            <p class="paragraph text-sm xl:text-base">
              Najlepszym miejscem do nauki dla mnie to YouTube. <b>Zwłaszcza kanał Naresh i Technologies</b> gdzie bardzo pozytywny Hindus
              z kaleczącym angielskim uczy programowania.Bynajmniej robi to bardzo dobrze :) 
            </p>
          </div>
          
        </div>
        <LandingTradingToolImage data-aos="fade-left" class="hidden sm:block" />
      </div>
    </section>

   
    <section class="w-full my-24" id="egzaminy">
      <div class="relative max-w-screen-xl px-8 mx-auto grid grid-cols-12 gap-x-6">
        <div data-aos="fade-right" class="col-span-12 lg:col-span-6">
          <div class="w-full">
            <img :src="require('~/assets/img/Logo_CKE.png')" class="w-full" alt="" />
          </div>
        </div>
        <div data-aos="fade-left" class="col-span-12 lg:col-span-5 space-y-8 sm:space-y-6 mt-8 xl:px-8">
          <h2 class="text-4xl font-semibold">Zadania egzaminacyjne</h2>
          <ul class="space-y-8 sm:space-y-4">
            <LandingListItem title="Źródła, z których pobierzesz egzaminy">
              <p class="text-sm text-gray-700 leading-relaxed">
                <!-- make two links -->
                <a href="https://arkusze.pl/egzamin-zawodowy-kwalifikacja-e-14/" target="_blank" class="text-header-gradient hover:text-header-gradient-hover">
                  https://arkusze.pl/egzamin-zawodowy-kwalifikacja-e-14/
                </a>
                <br/>
                <a href="https://arkusze.pl/egzamin-zawodowy-kwalifikacja-inf-03/" target="_blank" class="text-header-gradient hover:text-header-gradient-hover">
                  https://arkusze.pl/egzamin-zawodowy-kwalifikacja-inf-03/
                </a>
                <br/>
                <a href="https://www.testy.egzaminzawodowy.info/kwalifikacja-inf3/" target="_blank" class="text-header-gradient hover:text-header-gradient-hover">
                  https://www.testy.egzaminzawodowy.info/kwalifikacja-inf3
                </a>
              </p>
            </LandingListItem>
          </ul>
        </div>
      </div>
    </section>

    <!-- Getting started section -->
    <section class="bg-trading-tools relative max-w-full sm:mx-4 xl:mx-10 my-24 shadow sm:rounded-2xl overflow-hidden">
      <div class="w-full py-16 flex flex-col items-center">
        <h2 data-aos="flip-down" class="text-3xl sm:text-4xl font-semibold text-center">
          Zacznij pisać egzamin w 3 prostych krokach
        </h2>
        <div
          data-aos="fade-up"
          class="relative w-full flex flex-col lg:flex-row items-center justify-between space-y-12 lg:space-y-0 px-4 xl:px-10 mt-16 sm:mt-8"
        >
          <LandingStep v-for="step in steps" :key="step.title" :step="step" />
          <img
            :src="require('~/assets/img/getting-started/arrow.png')"
            class="hidden lg:inline-block absolute top-32 left-64 xl:left-[22rem] w-24 xl:w-[9.5rem]"
            alt=""
          />
          <img
            :src="require('~/assets/img/getting-started/arrow.png')"
            class="hidden lg:inline-block absolute top-32 right-64 xl:right-[22rem] w-24 xl:w-[9.5rem]"
            alt=""
          />
        </div>
      </div>
    </section>

    <!-- FAQ section -->
    <section class="w-full my-24">
      <BaseSection>
        <div data-aos="fade-right" data-aos-delay="150" class="col-span-12 lg:col-span-6">
          <div class="w-full">
            <img :src="require('~/assets/img/question.webp')" class="w-full" alt="" />
          </div>
        </div>
        <div data-aos="fade-left" data-aos-delay="150" class="col-span-12 lg:col-span-6 px-4 sm:px-6 mt-8">
          <span class="text-base text-gradient font-semibold uppercase mb-4 sm:mb-2">Pytania</span>
          <h2 class="text-3xl sm:text-4xl font-semibold mb-10 sm:mb-6">Częste pytania przed egzaminem</h2>

          <ul class="shadow-box">
            <BaseAccordion v-for="(accordion, index) in accordions" :key="index" :accordion="accordion" />
          </ul>
        </div>
      </BaseSection>
    </section>

    <div class="w-full my-10 flex justify-center">
      <a
        v-smooth-scroll
        data-aos="flip-down"
        data-aos-delay="150"
        href="#navbar"
        class="px-6 py-3 flex items-center space-x-2 bg-[#FAFAFA] hover:bg-gray-100 hover:shadow-md border border-[#DDDDDD] rounded-md text-gray-700"
      >
        <span>Wróć na górę</span>
        <ArrowUpIcon :size="20" />
      </a>
    </div>
  </div>
</template>

<script>
import aosMixin from '@/mixins/aos'
export default {
  name: 'IndexPage',
  mixins: [aosMixin],
  data() {
    return {
      accordions: [
        {
          title: 'Ile mam czasu na napisanie egzaminu?',
          description:
            "Na napisanie egzaminu praktycznego masz 150 minut od momentu zalogowania się. A osoby z papierami z poradnii mają dodatkowe 30 minut. Alee w głównej mierze wystarcza godzinka. :3",
        },
        {
          title: 'Czy jest dostęp do internetu?',
          description:
            "Jako że to egzamin z programowania to odpowiedź brzmi NIE. Nie ma dostępu do internetu. Ale możesz mieć kartkę z długopisem której nie sprawdzają to wiesz co możesz zrobić :p",
        },
        {
          title: 'Co muszę mieć przy sobie?',
          description:
            "Musisz mieć przy sobie dowód osobisty (legitymacje jeśli nie masz dowodu) oraz chęci do życia",
        },
        {
          title: 'Co jeśli nie zdam?',
          description:
            "Jeśli nie zdasz to masz rok czasu aby poprawić egzamin. Ale nie martw się, zdasz na pewno :3",
        },
      ],
      steps: [
        {
          img: 'download.png',
          title: 'Pobierz egzamin',
          description:
            'Wejdź na stronę arkusze.pl, testy.egzaminzawodowy.info, pobierz egzamin i wypakuj pliki',
        },
        {
          img: 'read.webp',
          title: 'Przygotuj się',
          description:
            'Przeczytaj bardzo dokładnie arkusz egzaminacyjny, zapoznaj się z zasadami egzaminu',
        },
        {
          img: 'code.webp',
          title: 'Zacznij pisać',
          description:
            'Pamiętaj że aby zdać trzeba mieć minimum 75%. *Taka podpowiedź: wystarczy przepisywać rzeczy z arkusza i masz już 50%* Powodzenia!',
        },
      ],
    }
  },
}
</script>
<style scoped>
.text-header-gradient {
  background: rgb(57, 132, 244);
  background: linear-gradient(169.4deg, #3984f4 -6.01%, #0cd3ff 36.87%, #2f7cf0 78.04%, #0e65e8 103.77%);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
.bg-partner {
  /* background: url('../assets/img/partner/background.png'); */
  background-size: cover;
  background-position: center;
}
.bg-trading-tools {
  background: url('../assets/img/bg-trading-tools.webp');
  background-size: cover;
  background-position: center;
}
.max-h-0 {
  max-height: 0;
}
</style>
