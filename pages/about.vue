<template>
  <div class="py-16 bg-white">
    <div class="container m-auto px-6 text-gray-600 md:px-12 xl:px-6">
      <div
        class="space-y-6 md:space-y-0 md:flex md:gap-6 lg:items-center lg:gap-12"
      >
        <div class="md:5/12 lg:w-5/12">
          <img
            src="../assets/medias/about.jpg"
            alt="image"
            loading="lazy"
            width=""
            height=""
          />
        </div>
        <div class="md:7/12 lg:w-6/12">
          <h2 class="text-2xl text-gray-900 font-bold md:text-4xl">
            The development of Vetements is carried out by passionate creators
          </h2>
          <p class="mt-6 text-gray-600">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eum omnis
            voluptatem accusantium nemo perspiciatis delectus atque autem!
            Voluptatum tenetur beatae unde aperiam, repellat expedita
            consequatur! Officiis id consequatur atque doloremque!
          </p>
          <p class="mt-4 mb-8 text-gray-600">
            Nobis minus voluptatibus pariatur dignissimos libero quaerat iure
            expedita at? Asperiores nemo possimus nesciunt dicta veniam
            aspernatur quam mollitia.
          </p>
          <a href="/">
            <button
              type="button"
              title="Start buying"
              class="w-full py-3 px-6 text-center rounded-xl transition bg-gray-700 shadow-xl hover:bg-gray-600 active:bg-gray-700 focus:bg-gray-600 sm:w-max"
            >
              <span class="block text-white font-semibold">
                Back <span>&#8635;</span></span
              >
            </button>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: "About",
});
</script>

<style scoped></style>
