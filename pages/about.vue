<template>
  <div class="px-5">
    <div class="flex flex-col gap-5">
      <div class="mt-[4rem]">
        <h1 class="text-4xl font-medium tracking-tighter max-w-[400px]">
          About our real estate firm
        </h1>
        <p class="text-gray-600 py-4">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel dolore
          dolorum omnis fuga esse obcaecati culpa sapiente assumenda voluptates
          quae!
        </p>
      </div>
      <div class="flex flex-col gap-3">
        <NuxtLink
          to="/"
          class="bg-zinc-900 text-white px-3 py-2 rounded-full cursor-pointer flex items-center justify-between gap-2"
        >
          Start exploring
          <div class="bg-white p-1 rounded-full">
            <img src="/assets/arrow_forward.png" class="h-6 invert" alt="" />
          </div>
        </NuxtLink>
        <NuxtLink
          to="/"
          class="cursor-pointer flex items-center justify-center gap-1"
        >
          Post properties
          <img
            src="/assets/chevron_right_24dp_E8EAED_FILL0_wght400_GRAD0_opsz24.png"
            alt=""
            class="h-6 invert"
          />
        </NuxtLink>
      </div>
    </div>
    <div class="py-10">
      <div>
        <img
          src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65ef8239a024dc5af672c85d_about-our-real-estate-firm-right-image-property-x-webflow-template.jpg"
          alt="About"
          class="rounded-md"
        />
      </div>
      <div class="my-7">
        <div class="">
          <h3 class="text-xl font-medium">Homes purchased</h3>
          <p class="text-4xl font-medium my-1">
            10k <span class="text-gray-500 -ml-3">+</span>
          </p>
          <p class="text-gray-600">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Autem, ea.
          </p>
        </div>
        <div class="mt-5">
          <h3 class="text-xl font-medium">Published properties</h3>
          <p class="text-4xl font-medium my-1">
            500 <span class="text-gray-500 -ml-2">k</span>
          </p>
          <p class="text-gray-600">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Autem, ea.
          </p>
        </div>
      </div>
    </div>
    <div class="mb-10">
      <div>
        <div class="text-black bg-gray-100 inline-block p-2 rounded-full">
          <div class="flex items-center gap-1">
            <img
              src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65e79f8d577d917fe3520a40_search-icon-property-x-webflow-template.svg"
              alt="Search Icon"
              class="bg-gray-300 p-1.5 rounded-full"
            />
            <span class="text-sm text-gray-800">Our values</span>
          </div>
        </div>
        <div>
          <h2 class="text-black text-4xl tracking-tight mt-5">
            The values that drive everything
          </h2>
          <p class="my-5 text-gray-600">
            Lorem ipsum dolor sit amet consectetur et ullamcorper morbi lectus
            fermentum viverra
          </p>
          <NuxtLink
            to="/"
            class="bg-zinc-900 text-white px-3 py-2 rounded-full cursor-pointer flex items-center justify-between gap-2"
          >
            Start exploring
            <div class="bg-white p-1 rounded-full">
              <img src="/assets/arrow_forward.png" class="h-6 invert" alt="" />
            </div>
          </NuxtLink>
        </div>
      </div>
      <div class="my-10 flex flex-col gap-10">
        <div class="border border-slate-100 p-5 rounded-md">
          <img
            src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65f06ff1f63fadbf3367dffa_inovation-icon-property-x-webflow-template.svg"
            alt="Innovation"
          />
          <h3 class="my-3 text-2xl tracking-tight">Innovation</h3>
          <p class="text-gray-600">
            Aenean viverra non mauris a ultrices pharetra libero varius ut
            adipiscing fusce velit.
          </p>
        </div>
        <div class="border border-slate-100 p-5 rounded-md">
          <img
            src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65f06ff2ac5a10700086ab17_excellence-icon-property-x-webflow-template.svg"
            alt="Excellence"
          />
          <h3 class="my-3 text-2xl tracking-tight">Excellence</h3>
          <p class="text-gray-600">
            Mi sollicitudin eu sem feugiat ultricies dictum amet purus eget
            viverra tortor odio mattis.
          </p>
        </div>
        <div class="border border-slate-100 p-5 rounded-md">
          <img
            src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65f06ff00fdbd04095895df7_growth-icon-property-x-webflow-template.svg"
            alt="Growth"
          />
          <h3 class="my-3 text-2xl tracking-tight">Growth</h3>
          <p class="text-gray-600">
            Sed hendrerit ac donec egestas orci lacinia porta ut egestas quisque
            nibh egestas sodales.
          </p>
        </div>
        <div class="border border-slate-100 p-5 rounded-md">
          <img
            src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65f06ff07db2e729dbc2ec78_teamwork-icon-property-x-webflow-template.svg"
            alt="Team work"
          />
          <h3 class="my-3 text-2xl tracking-tight">Team work</h3>
          <p class="text-gray-600">
            Non ut mauris libero tellus vel sed turpis hendrerit eu quam sed at
            ipsum elit bibendum est.
          </p>
        </div>
        <div class="border border-slate-100 p-5 rounded-md">
          <img
            src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65f06ff2afdfc5bcc00fb83b_communication-icon-property-x-webflow-template.svg"
            alt="Communication"
          />
          <h3 class="my-3 text-2xl tracking-tight">Communication</h3>
          <p class="text-gray-600">
            Lobortis eget cursus tempus venenatis enim sit placerat sit rutrum
            dui praesent vel.
          </p>
        </div>
        <div class="border border-slate-100 p-5 rounded-md">
          <img
            src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65f06ff1386bff34345bc2a0_ownership-icon-property-x-webflow-template.svg"
            alt="Ownership"
          />
          <h3 class="my-3 text-2xl tracking-tight">Ownership</h3>
          <p class="text-gray-600">
            Pretium quis amet dolor justo consequat risus mauris eget nulla non
            enim lacus pharetra.
          </p>
        </div>
      </div>
    </div>
    <div class="py-10 flex justify-center flex-col items-center">
      <div>
        <div class="text-black bg-gray-100 inline-block p-2 rounded-full">
          <div class="flex items-center gap-1">
            <img
              src="https://cdn.prod.website-files.com/65e5e5474c606fdc3f19a597/65e79f8a8726daa56714cb14_mail-icon-property-x-webflow-template.svg"
              alt="Mail Icon"
              class="bg-gray-300 p-1.5 rounded-full"
            />
            <span class="text-sm text-gray-800">Our Agents</span>
          </div>
        </div>
      </div>
      <div class="text-center">
        <h2 class="my-5 text-3xl tracking-tight">Meet our agents</h2>
        <p class="text-gray-600">
          Lorem ipsum dolor sit amet consectetur. Sit ut gravida aenean potenti.
          Metus in eu vel morbi dui nunc tellus. Non a massa maecenas massa.
        </p>

        <div class="mt-10 flex flex-col gap-10">
          <div class="border border-gray-300 p-5 rounded">
            <img
              src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/6522aae3a4ef7a6f93206b6a_Team_Avatar_5.jpg"
              alt="Agent"
              class="agent-pic"
            />
            <div class="text-center mt-3">
              <h4 class="font-bold text-gray-700">John Smith</h4>
              <p class="text-sm text-gray-600">Lead Agent</p>

              <div class="flex justify-center mt-5 gap-5">
                <a href="/about">
                  <img
                    src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/652248ce6255a39c3d816eef_LinkedIn.png"
                    alt="Linked In"
                    class="social-img"
                  />
                </a>
                <a href="/about">
                  <img
                    src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/652248cfd14bf95324645f1b_X.png"
                    alt="Twitter"
                    class="social-img"
                  />
                </a>
              </div>
            </div>
          </div>

          <div class="border border-gray-300 p-5 rounded">
            <img
              src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/6522aae37c23f39276c3ccbd_Team_Avatar_6.jpg"
              alt="Agent"
              class="agent-pic"
            />
            <div class="text-center mt-3">
              <h4 class="font-bold text-gray-700">Emily Davis</h4>
              <p class="text-sm text-gray-600">Senior Sales Agent</p>

              <div class="flex justify-center mt-5 gap-5">
                <a href="/about">
                  <img
                    src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/652248ce6255a39c3d816eef_LinkedIn.png"
                    alt="Linked In"
                    class="social-img"
                  />
                </a>
                <a href="/about">
                  <img
                    src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/652248cfd14bf95324645f1b_X.png"
                    alt="Twitter"
                    class="social-img"
                  />
                </a>
              </div>
            </div>
          </div>

          <div class="border border-gray-300 p-5 rounded">
            <img
              src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/6522aae36a63b8b3ab676b71_Team_Avatar_2.jpg"
              alt="Agent"
              class="agent-pic"
            />
            <div class="text-center mt-3">
              <h4 class="font-bold text-gray-700">Michael Brown</h4>
              <p class="text-sm text-gray-600">Investment Expert</p>

              <div class="flex justify-center mt-5 gap-5">
                <a href="/about">
                  <img
                    src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/652248ce6255a39c3d816eef_LinkedIn.png"
                    alt="Linked In"
                    class="social-img"
                  />
                </a>
                <a href="/about">
                  <img
                    src="https://cdn.prod.website-files.com/651fc01488b25b66e6353ec9/652248cfd14bf95324645f1b_X.png"
                    alt="Twitter"
                    class="social-img"
                  />
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div></div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
