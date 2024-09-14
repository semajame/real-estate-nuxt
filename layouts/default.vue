<template>
  <div class="bg-color">
    <header class="border-gray-200 py-5 px-4 flex items-center justify-between">
      <NuxtLink to="/" class="cursor-pointer">
        <img
          src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65e5fa6e0a2bd07399b457a7_property-logo-text-property-x-webflow-template.svg"
          class="h-7"
          alt="Logo"
        />
      </NuxtLink>
      <div class="md:hidden flex flex-wrap items-center justify-between px-4">
        <div class="grid justify-items-center gap-1.5" @click="openNav">
          <span
            class="h-0.5 w-8 rounded-full bg-black transform ease duration-200"
            id="first"
          ></span>
          <span
            class="h-0.5 w-8 rounded-full bg-black transform ease duration-200"
            id="second"
          ></span>
          <span
            class="h-0.5 w-8 rounded-full bg-black transform ease duration-200"
            id="third"
          ></span>
        </div>

        <div
          class="hidden w-full absolute bg-color z-10 transition ease duration-200 top-12 left-0 right-0 bottom-0 h-100"
          id="navbar-hamburger"
        >
          <ul
            class="flex flex-col mt-5 pt-10 right-5 absolute text-right bg-transparent text-white text-3xl"
          >
            <li>
              <NuxtLink
                to="/"
                @click="closeNav"
                class="block py-4 px-3 text-black"
                >Home</NuxtLink
              >
            </li>
            <li>
              <NuxtLink
                to="/about"
                @click="closeNav"
                class="block py-4 px-3 text-black"
                >About</NuxtLink
              >
            </li>
            <li>
              <NuxtLink
                to="/contact"
                @click="closeNav"
                class="block py-4 px-3 text-black"
                >Contact</NuxtLink
              >
            </li>
            <li>
              <NuxtLink
                to="/listing"
                @click="closeNav"
                class="block pt-2 pb-3 px-3 text-black"
                >Listing</NuxtLink
              >
            </li>
          </ul>
        </div>
      </div>

      <ul class="hidden md:flex font-medium mt-4">
        <li>
          <NuxtLink to="/" class="block px-3 text-black">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about" class="block px-3 text-black">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/contact" class="block px-3 text-black"
            >Contact</NuxtLink
          >
        </li>
        <li>
          <NuxtLink to="/listing" class="block text-black px-3"
            >Listing</NuxtLink
          >
        </li>
      </ul>
    </header>
    <div class="mx-auto">
      <slot />
    </div>
    <Footer />
  </div>
</template>

<script setup>
const openNav = () => {
  const nav = document.querySelector("#navbar-hamburger");
  const first = document.querySelector("#first");
  const second = document.querySelector("#second");
  const third = document.querySelector("#third");
  const firstClass = [
    "transform",
    "translate-y-1",
    "scale-200",
    "rotate-45",
    "ease",
  ];
  const secondClass = ["hidden", "opacity-0", "ease", "duration-300"];
  const thirdClass = [
    "transform",
    "-translate-y-1",
    "scale-200",
    "-rotate-45",
    "ease",
  ];

  if (nav) {
    nav.classList.toggle("hidden");
    firstClass.forEach((cls) => {
      first.classList.toggle(cls);
    });
    secondClass.forEach((cls) => {
      second.classList.toggle(cls);
    });
    thirdClass.forEach((cls) => {
      third.classList.toggle(cls);
    });
  }
};

const closeNav = () => {
  openNav();
};
</script>
