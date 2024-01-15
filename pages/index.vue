<template>
  <div class="bg-black min-h-screen overflow-hidden relative">
    <div class="flex flex-row flex-wrap h-screen p-8 font-index relative z-10">
      <div
        class="text-4xl md:text-5xl lg:text-7xl text-gray-200 flex flex-col justify-center items-center lg:items-start w-full lg:w-1/2 tracking-wider gap-10 font-index no-wrap pt-10 lg:pt-0 pb-0 lg:pb-32 relative z-20"
      >
        <h1>Welcome to 3D world</h1>
        <h1>Design for the future</h1>
        <div class="flex flex-col pt-8 md:pt-14 items-start">
          <div class="text-3xl">
            <NuxtLink
              target="_blank"
              to="https://www.linkedin.com/in/aysegulkaradan/"
              class="mx-4 text-gray-50 hover:text-[#2272FF]"
              alt="linkedin"
              aria-label="connect with linkedin"
            >
              <Icon name="uil:linkedin" class="text-5xl md:text-7xl" />
            </NuxtLink>
            <NuxtLink
              target="_blank"
              to="mailto:karadan.ay7@gmail.com"
              class="mx-4 text-gray-50 hover:text-[#2272FF]"
              alt="mailto"
              aria-label="connect with mail"
            >
              <Icon name="uil:envelope" class="text-5xl md:text-7xl" />
            </NuxtLink>
            <NuxtLink
              target="_blank"
              alt="github"
              to="https://github.com/karadanay7"
              class="mx-4 text-gray-50 hover:text-[#2272FF]"
              aria-label="connect with github"
            >
              <Icon name="uil:github" class="text-5xl md:text-7xl" />
            </NuxtLink>

            <h2 class="text-2xl md:text-3xl text-gray-50 text-center m-3">
              Aysegul Karadan
            </h2>
          </div>
        </div>
      </div>
    </div>
    <div class="absolute top-0 left-1/3 w-full h-full z-0">
      <iframe
        src="https://my.spline.design/3ddna-5e0a6891697f92dd1061bcc09ceb4b5a/"
        frameborder="0"
        width="100%"
        height="100%"
      ></iframe>
    </div>
  </div>
</template>

<script setup></script>
