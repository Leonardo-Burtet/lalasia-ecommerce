<template>
  <div class="bg-white-500">
    <!-- <HeaderComponentVue /> -->
    <main class="container mx-auto py-14 flex flex-col gap-44">
      <section class="relative">
        <h1 class="w-full text-center text-6xl font-bold leading-[4.5rem]">
          Discover Furniture With<br />
          High Quality Wood
        </h1>
        <p class="w-full py-8 text-center text-paragraph font-medium">
          Pellentesque etiam blandit in tincidunt at donec. Eget ipsum dignissim
          placerat nisi,<br />
          adipiscing mauris non. Purus parturient viverra nunc, tortor sit
          laoreet. Quam tincidunt<br />
          aliquam adipiscing tempor.
        </p>
        <img
          src="/icons/icon-arrow.svg"
          alt=""
          srcset=""
          class="absolute top-0 2xl:left-[150px]"
        />
        <div
          class="z-20 relative max-w-[810px] w-full h-[80px] bg-[#FFFFFF] mx-auto p-4 flex justify-between mb-[-40px]"
        >
          <input id="property" type="text" name="property" />
          <button
            class="max-w-[170px] bg-green-dark-600 w-full h-[54px] text-[#FFFFFF] font-semibold"
          >
            Search
          </button>
        </div>
        <img class="z-10" src="imagens/moveisinput.png" alt="" srcset="" />
      </section>
      <section class="flex flex-col gap-12">
        <div class="flex justify-between">
          <div class="flex flex-col">
            <h2 class="font-bold text-[#FFB23F] mb-4">Benefits</h2>
            <p class="text-5xl font-bold">
              Benefits when using <br />
              our services
            </p>
          </div>
          <p class="text-lg flex items-end text-paragraph font-medium">
            Pellentesque etiam blandit in tincidunt at donec. Eget ipsum
            <br />dignissim placerat nisi, adipiscing mauris non purus<br />
            parturient.
          </p>
        </div>
        <div class="flex justify-between">
          <div
            class="h-[285px] w-[394px] bg-screen-white p-6 flex flex-col gap-6"
          >
            <span class="w-16 h-16"
              ><img src="icons/icon-threesquares.svg" alt="" srcset=""
            /></span>
            <p class="text-2xl font-bold">Many Choices</p>
            <p class="text-lg font-medium text-paragraph">
              Pellentesque etiam blandit in tincidunt at donec. Eget ipsum
              dignissim placerat nisi, adipiscing mauris non.
            </p>
          </div>
          <div
            class="h-[285px] w-[394px] bg-screen-white p-6 flex flex-col gap-6"
          >
            <span class="w-16 h-16"
              ><img src="icons/icon-calendar.svg" alt="" srcset=""
            /></span>
            <p class="text-2xl font-bold">Fast and On Time</p>
            <p class="text-lg font-medium text-paragraph">
              Pellentesque etiam blandit in tincidunt at donec. Eget ipsum
              dignissim placerat nisi, adipiscing mauris non.
            </p>
          </div>
          <div
            class="h-[285px] w-[394px] bg-screen-white p-6 flex flex-col gap-6"
          >
            <span class="w-16 h-16">
              <img src="icons/icon-money.svg" alt="" srcset="" />
            </span>
            <p class="text-2xl font-bold">Affordable Price</p>
            <p class="text-lg font-medium text-paragraph">
              Pellentesque etiam blandit in tincidunt at donec. Eget ipsum
              dignissim placerat nisi, adipiscing mauris non.
            </p>
          </div>
        </div>
      </section>

      <section class="flex flex-col">
        <div class="w-[656px] mx-auto text-center">
          <h2 class="font-bold text-[#FFB23F] mb-4">Product</h2>
          <p class="text-5xl font-bold mb-8">Our popular product</p>
          <p class="text-lg font-medium text-paragraph">
            Pellentesque etiam blandit in tincidunt at donec. Eget ipsum
            dignissim placerat nisi, adipiscing mauris non purus parturient.
          </p>
        </div>
        <vue-glide>
          <vue-glide-slide
            ><div class="w-14 h-14 bg-brown-500"></div>
            1</vue-glide-slide
          >
          <vue-glide-slide
            ><div class="w-14 h-14 bg-brown-500"></div>
            2</vue-glide-slide
          >
          <vue-glide-slide
            ><div class="w-14 h-14 bg-[#FFFFFF]"></div>
            3</vue-glide-slide
          >
        </vue-glide>
      </section>
      <!--
      <section>
        <h2>Our Product</h2>
        <div class="flex justify-between">
          <div>
            <p>Crafted by talented and high quality material</p>
            <p>
              Pellentesque etiam blandit in tincidunt at donec. Eget ipsum
              <br />
              dignissim placerat nisi, adipiscing mauris non purus parturient.
              <br />
              morbi fermentum, vivamus et accumsan dui tincidunt pulvinar
            </p>

            <button>Learn More</button>

            imagem
          </div>
          <div>
            <div>
              <span>Years Experience</span>
              <span>Years Experience</span>
              <span>Years Experience</span>
            </div>
            imagem
          </div>
        </div>
      </section>

      <section>
        <h2>Testimonials</h2>
        <p>What our customer say</p>
        <p>
          Pellentesque etiam blandit in tincidunt at donec. Eget ipsum dignissim
          <br />
          placerat nisi, adipiscing mauris non purus parturient.
        </p>
        <div class="flex flex-nowrap overflow-x-scroll">
          <div class="mx-3 h-[256px] min-w-[545px] bg-brown-500"></div>
          <div class="mx-3 h-[256px] min-w-[545px] bg-brown-500"></div>
          <div class="mx-3 h-[256px] min-w-[545px] bg-brown-500"></div>
        </div>
      </section>

      <section>
        <h2>Articles</h2>
        <div class="flex justify-between">
          <div>
            <p>The best furniture comes from Lalasia</p>
            <p>Pellentesque etiam blandit in tincidunt at donec.</p>
            imagemslide
          </div>
          <div class="flex flex-col justify-between">
            <div class="h-[260px] min-w-[260px] bg-brown-500"></div>
            <div class="h-[260px] min-w-[260px] bg-brown-500"></div>
            <div class="h-[260px] min-w-[260px] bg-brown-500"></div>
          </div>
        </div>
      </section>

      <section class="flex justify-between">
        <h3>Join with me to get special discount</h3>
        <button>Learn More -></button>
      </section> -->
    </main>

    <!-- <FooterComponentVue /> -->
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
