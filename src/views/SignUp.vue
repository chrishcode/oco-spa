<template>
  <section class="bg-white h-full py-8">
    <div class="container mx-auto h-full px-4">
      <h1 class="text-grey-darker text-4xl xl:text-5xl lg:text-5xl md:text-5xl font-bold leading-tight tracking-tight mb-8">Sign up</h1>
      <form class="w-full max-w-sm text-sm">
        <div class="flex flex-wrap -mx-3 mb-6">
          <div class="w-full px-3">
            <label class="block uppercase tracking-wide text-grey-darker text-xs font-bold mb-2" for="grid-name">
              Name
            </label>
            <input class="appearance-none block w-full bg-grey-lighter text-grey-darker rounded py-3 px-4 mb-3 leading-tight" id="grid-name" type="text" placeholder="Christopher Wohlfarth">
          </div>
        </div>
        <div class="flex flex-wrap -mx-3 mb-6">
          <div class="w-full px-3">
            <label class="block uppercase tracking-wide text-grey-darker text-xs font-bold mb-2" for="grid-email">
              Email address
            </label>
            <input class="appearance-none block w-full bg-grey-lighter text-grey-darker rounded py-3 px-4 mb-3 leading-tight" id="grid-email" type="text" placeholder="example@email.com">
          </div>
        </div>
        <div class="flex flex-wrap -mx-3 mb-6">
          <div class="w-full px-3">
            <label class="block uppercase tracking-wide text-grey-darker text-xs font-bold mb-2" for="grid-password">
              Password
            </label>
            <input class="appearance-none block w-full bg-grey-lighter text-grey-darker border border-grey-lighter rounded py-3 px-4 mb-3 leading-tight" id="grid-password" type="password" placeholder="******************">
            <p class="text-grey-dark text-xs italic">Make it as long and as crazy as you'd like</p>
          </div>
        </div>
      </form>
    </div>
  </section>
</template>
