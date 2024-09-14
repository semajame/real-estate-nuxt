<template>
  <div class="p-5 bg-zinc-950 rounded-xl">
    <div class="flex flex-col gap-3">
      <h3 class="text-white text-2xl">
        Discover exclusive real estate opportunities
      </h3>
      <p class="text-gray-600">
        Lorem ipsum dolor sit amet consectetur. Egestas eu amet dictum tellus.
        Purus morbi lorem viverra cras.
      </p>
      <div class="my-5 flex flex-col gap-3">
        <input
          type="text"
          name=""
          id=""
          placeholder="Enter your email address"
          class="text-white bg-zinc-800 rounded-full p-3"
        />
        <button
          class="text-zinc-950 bg-white pl-3 pr-2 py-2 flex justify-between items-center rounded-full"
        >
          Subscribe
          <img
            src="/assets/arrow_forward.png"
            alt="Arrow"
            class="w-7 bg-zinc-800 rounded-full"
          />
        </button>
        <div></div>
      </div>
      <div>
        <h3 class="text-white text-2xl">Contact Us</h3>
        <div class="flex flex-col gap-5 my-10">
          <div class="flex items-center gap-5">
            <div>
              <img
                src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65e73b98069b3ccda17a9cb5_email-icon-property-x-webflow-template.svg"
                alt="Email"
              />
            </div>
            <div class="flex flex-col gap-1">
              <p class="text-zinc-500">Email address</p>
              <p class="text-white">info@home.com</p>
            </div>
          </div>
          <div class="flex items-center gap-5">
            <div>
              <img
                src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65e73b97a231c2632193429b_phone-icon-property-x-webflow-template.svg"
                alt="Phone"
              />
            </div>
            <div class="flex flex-col gap-1">
              <p class="text-zinc-500">Phone number</p>
              <p class="text-white">(123)456 - 789</p>
            </div>
          </div>
          <div class="flex items-center gap-5">
            <div>
              <img
                src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65e73b98aff9a9e691a1c48d_help-and-support-icon-property-x-webflow-template.svg"
                alt="Help"
              />
            </div>
            <div class="flex flex-col gap-1">
              <p class="text-zinc-500">Help and support</p>
              <p class="text-white">support@home.com</p>
            </div>
          </div>
        </div>
      </div>
      <div class="flex justify-center my-5">
        <NuxLink to="/" class="cursor-pointer">
          <img
            src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65e5fa6e0a2bd07399b457a7_property-logo-text-property-x-webflow-template.svg"
            class="h-7 invert"
            alt="Logo"
          />
        </NuxLink>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
