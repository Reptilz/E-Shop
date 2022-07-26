<template>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
    integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />
  <nav class="flex items-center justify-between flex-wrap bg-teal-500 p-6">
    <div class="flex items-center flex-shrink-0 text-white mr-6">
      <NuxtLink to="/">
        <span class="font-semibold text-xl tracking-tight">StreetLoop</span>
      </NuxtLink>
    </div>
    <div class="block lg:hidden">
      <button
        class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white"
      >
        <svg
          class="fill-current h-3 w-3"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg"
        >
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
      <div class="text-l lg:flex-grow">
        <NuxtLink
          to="shop"
          key="shop"
          class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4"
        >
          Shop
        </NuxtLink>
        <NuxtLink
          to="/about"
          class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white ml-2"
        >
          About us
        </NuxtLink>
      </div>
      <div>
        <div class="pt-2 mr-12 relative mx-auto text-gray-600">
          <input
            class="border-2 border-gray-300 bg-white h-10 px-5 pr-16 rounded-lg text-sm focus:outline-none"
            type="search"
            name="search"
            placeholder="Search"
          />
          <button type="submit" class="absolute right-0 top-0 mt-5 mr-4">
            <svg
              class="text-gray-600 h-4 w-4 fill-current"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              version="1.1"
              id="Capa_1"
              x="0px"
              y="0px"
              viewBox="0 0 56.966 56.966"
              style="enable-background: new 0 0 56.966 56.966"
              xml:space="preserve"
              width="512px"
              height="512px"
            >
              <path
                d="M55.146,51.887L41.588,37.786c3.486-4.144,5.396-9.358,5.396-14.786c0-12.682-10.318-23-23-23s-23,10.318-23,23  s10.318,23,23,23c4.761,0,9.298-1.436,13.177-4.162l13.661,14.208c0.571,0.593,1.339,0.92,2.162,0.92  c0.779,0,1.518-0.297,2.079-0.837C56.255,54.982,56.293,53.08,55.146,51.887z M23.984,6c9.374,0,17,7.626,17,17s-7.626,17-17,17  s-17-7.626-17-17S14.61,6,23.984,6z"
              />
            </svg>
          </button>
        </div>
      </div>
    </div>
    <NuxtLink
      to="/bag"
      key="bag"
      class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4 ml-20"
    >
      <img id="bag" src="../assets/medias/bag.png" alt="" />
      <p>Bag(0)</p>
    </NuxtLink>
    <NuxtLink
      to="/user"
      key="user"
      class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-12 ml-2"
    >
      <img
        id="user-logo"
        src="../assets/medias/abstract-user-flat-1.png"
        alt=""
      />
      <p>Jordan</p>
    </NuxtLink>
  </nav>
</template>

<style scoped>
#user-logo {
  width: 40px;
  height: 40px;
}
#bag {
  width: 40px;
  height: 40px;
}
</style>
