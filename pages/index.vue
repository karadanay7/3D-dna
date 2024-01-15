<template>
  <div class="min-h-screen bg-black overflow-hidden">
    <div class="flex flex-row h-screen w-full font-index">
      <div
        class="absolute sm:relative text-3xl md:text-5xl lg:text-6xl text-gray-200 flex flex-col w-full lg:w-1/2 tracking-wider font-index pt-44 lg:pt-20 p-4 md:pl-12"
      >
        <h1>Welcome to 3D world, Design for the Future</h1>

        <div class="flex flex-col pt-8 md:pt-14">
          <div class="text-3xl">
            <NuxtLink
              target="_blank"
              to="https://www.linkedin.com/in/aysegulkaradan/"
              class="mx-4 text-gray-50 hover:text-[#2272FF]"
              alt="linkedin"
              aria-label="connect with linkedin"
            >
              <Icon name="uil:linkedin" class="text-3xl md:text-5xl" />
            </NuxtLink>
            <NuxtLink
              target="_blank"
              to="mailto:karadan.ay7@gmail.com"
              class="mx-4 text-gray-50 hover:text-[#2272FF]"
              alt="mailto"
              aria-label="connect with mail"
            >
              <Icon name="uil:envelope" class="text-3xl md:text-5xl" />
            </NuxtLink>
            <NuxtLink
              target="_blank"
              alt="github"
              to="https://github.com/karadanay7"
              class="mx-4 text-gray-50 hover:text-[#2272FF]"
              aria-label="connect with github"
            >
              <Icon name="uil:github" class="text-3xl md:text-5xl" />
            </NuxtLink>

            <h2 class="text-sm text-gray-50 p-4">Aysegul Karadan</h2>
          </div>
        </div>
      </div>
      <div class="w-full lg:w-1/2 h-full overflow-hidden">
        <iframe
          src="https://my.spline.design/3ddna-5e0a6891697f92dd1061bcc09ceb4b5a/"
          frameborder="0"
          width="100%"
          height="100%"
        ></iframe>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
