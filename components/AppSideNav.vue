<template>
  <nav
    class="justify-between hidden min-h-screen py-8 sm:flex-col sm:flex w-80"
  >
    <AppLogo class="w-40 mx-auto" />

    <div class="flex-col hidden gap-4 mx-auto mb-24 w-44">
      <a class="flex gap-4 text-[#224D8C] font-bold" href="#">
        <span
          class="flex items-center justify-center rounded-full w-7 h-7 bg-slate-200"
        >
          <span class="block w-4 h-4 rounded-full bg-[#224D8C]"></span>
        </span>

        Home
      </a>

      <a class="flex gap-4 font-bold text-gray-500" href="#">
        <span
          class="flex items-center justify-center rounded-full w-7 h-7 bg-slate-200"
        >
          <span class="hidden w-4 h-4 rounded-full bg-[#224D8C]"></span>
        </span>

        Portfolio
      </a>

      <a class="flex gap-4 font-bold text-gray-500" href="#">
        <span
          class="flex items-center justify-center rounded-full w-7 h-7 bg-slate-200"
        >
          <span class="hidden w-4 h-4 rounded-full bg-[#224D8C]"></span>
        </span>

        Contact
      </a>
    </div>

    <div class="flex gap-2 mx-auto">
      <a href="https://www.facebook.com/DougDesignReal/" target="_blank">
        <img
          src="/social-facebook-icon.svg"
          alt="facebook"
          width="38"
          height="38"
        />
      </a>

      <a href="https://www.instagram.com/doouglopes/" target="_blank">
        <img
          src="/social-instagram-icon.svg"
          alt="instagram"
          width="38"
          height="38"
        />
      </a>

      <a href="https://twitter.com/DougLopesReal" target="_blank">
        <img
          src="/social-twitter-icon.svg"
          alt="twitter"
          width="38"
          height="38"
        />
      </a>
    </div>
  </nav>
</template>
