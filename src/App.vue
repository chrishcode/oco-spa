<template>
  <div id="app">
    <div id="nav">
      <header class="pin-t w-full z-10">
        <div class="container mx-auto px-4 py-50px flex items-center justify-between">
          <a href="/" class="flex items-center text-brand no-underline">
            <img class="w-12" src="oco-logo.png" alt="logo" />
            <span class="text-base tracking-tight font-bold ml-2 flex flex-row items-center"></span>
          </a>
          <div class="flex items-center">
            <router-link class="no-underline" to="/"><a class="bg-transparant py-2 px-4 text-sm font-bold leading-normal text-grey no-underline ml-2 uppercase" href="#">Home</a></router-link>
            <router-link class="no-underline" to="/sign-up"><a class="bg-transparant py-2 px-4 text-sm font-bold leading-normal text-grey no-underline ml-2 uppercase" href="#">Sign Up</a></router-link>
            <router-link class="no-underline" to="/sign-in"><a class="bg-transparant py-2 px-4 text-sm font-bold leading-normal text-grey no-underline ml-2 uppercase" href="#">Sign In</a></router-link>
          </div>
        </div>
      </header>
    </div>
    <router-view />
  </div>
</template>

<style>
</style>
