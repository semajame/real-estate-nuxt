<template>
  <div class="m-5">
    <div class="text-center my-10">
      <div class="text-4xl">Contacts</div>
      <p class="p-3">
        Get in Touch with and we will respond to your within 1-2 Business Days
      </p>
    </div>
    <div class="my-20">
      <div>
        <div>
          <h2 class="text-4xl">Get in touch</h2>
          <p></p>
        </div>
        <div>
          <form action="" class="flex flex-col gap-5">
            <div class="flex flex-col mt-10">
              <label for="email" class="text-gray-800"> Email: </label>
              <input
                type="text"
                placeholder="email:"
                name="email"
                class="p-3 rounded-md border outline-none my-2"
              />
            </div>
            <div class="flex flex-col">
              <label for="username" class="text-gray-800"> Full Name: </label>
              <input
                type="text"
                placeholder="fullname:"
                name="username"
                class="p-3 rounded-md border outline-none my-2"
              />
            </div>
            <div class="flex flex-col">
              <label for="message" class="text-gray-800"> Message: </label>
              <textarea
                placeholder="message:"
                class="p-3 rounded-md border outline-none my-2"
              />
            </div>
            <input
              type="submit"
              placeholder="Submit"
              value="Submit"
              class="bg-black text-white p-2 rounded-full cursor-pointer"
            />
          </form>
        </div>
      </div>
      <div class="my-10">
        <img
          src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a5c2/65e8d3279075f728c66b117c_executive-office-san-diego-thumbnail-v1-property-x-webflow-template.jpg"
          alt="house image"
          class="rounded-md"
        />
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
