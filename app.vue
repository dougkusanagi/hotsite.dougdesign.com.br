<script setup>
useHead({
  htmlAttrs: {
    lang: "en",
  },
  meta: [
    {
      name: "description",
      content:
        "I'm Douglas Lopes, a Frelancer Designer and Full Stack Dev. I design logos, websites and code in Javascript and PHP since 2014.",
    },
  ],
});

useSeoMeta({
  title: "Douglas Lopes",
  description:
    "I'm Douglas Lopes, a Frelancer Designer and Full Stack Dev. I design logos, websites and code in Javascript and PHP since 2014.",
  ogTitle: "Douglas Lopes",
  ogDescription:
    "I'm Douglas Lopes, a Frelancer Designer and Full Stack Dev. I design logos, websites and code in Javascript and PHP since 2014.",
  ogImage: "https://hotsite.dougdesign.com.br/DG-logo-icon.png",
  twitterCard: "summary_large_image",
  twitterCreator: "@DougLopesReal",
  twitterTitle: "Douglas Lopes",
  twitterDescription:
    "I'm Douglas Lopes, a Frelancer Designer and Full Stack Dev. I design logos, websites and code in Javascript and PHP since 2014.",
});
</script>

<template>
  <header>
    <title>Douglas Lopes</title>
  </header>

  <div class="flex">
    <AppSideNav />

    <main
      class="flex-1 max-w-full bg-gray-100 sm:mt-4 sm:ml-4 sm:rounded-tl-xl"
    >
      <article class="flex flex-col gap-6 mx-4 mt-10 sm:mt-12 sm:mx-14">
        <img
          class="mx-auto rounded-full shadow sm:mx-0 w-52 sm:w-48"
          src="/douglas-lopes-fotografia-p&b.png"
          alt="fotografia p&b de Douglas Lopes "
          width="208"
          height="216"
        />

        <div class="flex flex-col gap-2">
          <h2 class="text-xl font-bold text-yellow-700">
            Hi, i'm Douglas Lopes
          </h2>

          <p class="text-4xl text-[#5d748f]">
            I'm a Frelancer Designer and Full Stack Dev. I design logos,
            websites and code in Javascript and PHP since 2014.
          </p>
        </div>

        <div class="flex flex-col gap-4 sm:flex-row">
          <a
            href="#"
            class="bg-white text-[#4c79af] font-medium w-full sm:w-44 h-14 flex items-center justify-center rounded-lg shadow hover:bg-slate-100 hover:translate-y-[2px] hover:shadow-none hover:border hover:border-white transition-all duration-100"
          >
            My Work
          </a>

          <a
            href="#"
            class="bg-[#224D8C] font-medium w-full sm:w-44 h-14 flex items-center justify-center rounded-lg shadow text-white hover:brightness-90 hover:translate-y-[2px]"
          >
            Let's Talk
          </a>
        </div>
      </article>

      <article class="flex flex-col gap-6 mx-4 mt-16 sm:mx-14">
        <div class="flex flex-col gap-2">
          <h2 class="text-xl font-bold text-yellow-700">Some recent works</h2>

          <div class="flex gap-4 mt-3">
            <div
              class="flex items-center justify-center font-medium transition-all duration-100 bg-white rounded-lg shadow grayscale hover:translate-y-[2px] w-72 h-28 hover:grayscale-0"
            >
              <img
                class="max-h-24"
                src="/portfolio-logo-1.svg"
                alt="Logo Cantinho do Podcast"
                width="111"
                height="111"
              />
            </div>

            <div
              class="bg-[#1B2533] grayscale font-medium w-72 h-28 flex items-center justify-center rounded-lg shadow hover:grayscale-0 hover:translate-y-[2px] transition-all duration-100"
            >
              <img
                class="max-h-20"
                src="/portfolio-logo-2.svg"
                alt="Logo Cordeiro Advogados"
                width="70"
                height="80"
              />
            </div>

            <div
              class="flex items-center justify-center font-medium transition-all duration-100 bg-white rounded-lg shadow grayscale hover:translate-y-[2px] w-72 h-28 hover:grayscale-0"
            >
              <img
                class="max-h-24"
                src="/portfolio-logo-3.svg"
                alt="Logo Escola Nossa Senhora de Fátima"
                width="95"
                height="96"
              />
            </div>
          </div>
        </div>
      </article>
    </main>
  </div>
</template>
