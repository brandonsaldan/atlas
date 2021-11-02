<template>
  <body class="antialiased bg-gray-900 text-white">
    <div class="max-w-3xl px-4 mx-auto sm:px-6 xl:max-w-5xl xl:px-0">
      <div class="flex flex-col justify-between h-screen">
        <main class="mb-auto">
          <div class="divide-y divide-gray-200 dark:divide-gray-700 animate__animated animate__fadeIn">
            <div class="pt-6 pb-8 space-y-2 md:space-y-5">
              <h1 class="text-3xl font-extrabold leading-9 tracking-tight text-gray-900 dark:text-gray-100 sm:text-4xl sm:leading-10 md:text-6xl md:leading-14">Projects</h1>
            </div>
            <ul class="divide-y divide-gray-200 dark:divide-gray-700">
                <li class="py-12">

                  <div class="flex flex-wrap">

                    <div class="">
                      <div class="flex flex-wrap -m-4">
                        <div class="p-4 md:w-1/2 md" style="max-width: 544px;">
                          <div class="h-full overflow-hidden border-2 border-gray-200 rounded-md border-opacity-60 dark:border-gray-700">
                            <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/fox" aria-label="link">
                            </a>
                            <div class="p-6">
                            <h2 class="mb-3 text-2xl font-bold leading-8 tracking-tight">
                              <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/fox" aria-label="link">fox</a>
                            </h2>
                            <p class="mb-3 prose text-gray-500 max-w-none dark:text-gray-400">🦊 social media username scraping discord bot</p>
                              <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/fox" class="text-base font-medium leading-6 text-primary-500 hover:text-primary-600 dark:hover:text-primary-400" aria-label="link">github →</a>
                            </div>
                          </div>
                        </div>
                        <div class="p-4 md:w-1/2 md" style="max-width: 544px;">
                          <div class="h-full overflow-hidden border-2 border-gray-200 rounded-md border-opacity-60 dark:border-gray-700">
                            <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/atlas" aria-label="link">
                            </a>
                            <div class="p-6">
                            <h2 class="mb-3 text-2xl font-bold leading-8 tracking-tight">
                              <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/atlas" aria-label="link">atlas</a>
                            </h2>
                            <p class="mb-3 prose text-gray-500 max-w-none dark:text-gray-400">📰 personal website built with vue.js and tailwind</p>
                              <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/atlas" class="text-base font-medium leading-6 text-primary-500 hover:text-primary-600 dark:hover:text-primary-400" aria-label="link">github →</a>
                            </div>
                          </div>
                        </div>
                        <div class="p-4 md:w-1/2 md" style="max-width: 544px;">
                          <div class="h-full overflow-hidden border-2 border-gray-200 rounded-md border-opacity-60 dark:border-gray-700">
                            <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/ticker" aria-label="link">
                            </a>
                            <div class="p-6">
                            <h2 class="mb-3 text-2xl font-bold leading-8 tracking-tight">
                              <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/ticker" aria-label="link">ticker</a>
                            </h2>
                            <p class="mb-3 prose text-gray-500 max-w-none dark:text-gray-400">💸 stock and cryptocurrency discord bot</p>
                              <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/ticker" class="text-base font-medium leading-6 text-primary-500 hover:text-primary-600 dark:hover:text-primary-400" aria-label="link">github →</a>
                            </div>
                          </div>
                        </div>
                        <div class="p-4 md:w-1/2 md" style="max-width: 544px;">
                          <div class="h-full overflow-hidden border-2 border-gray-200 rounded-md border-opacity-60 dark:border-gray-700">
                            <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/mockingbird" aria-label="link">
                            </a>
                            <div class="p-6">
                            <h2 class="mb-3 text-2xl font-bold leading-8 tracking-tight">
                              <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/mockingbird" aria-label="link">mockingbird</a>
                            </h2>
                            <p class="mb-3 prose text-gray-500 max-w-none dark:text-gray-400">🐦tweet tweet (watch this space, coming soon)</p>
                              <a target="_blank" rel="noopener noreferrer" href="https://github.com/brandonsaldan/mockingbird" class="text-base font-medium leading-6 text-primary-500 hover:text-primary-600 dark:hover:text-primary-400" aria-label="link">github →</a>
                            </div>
                          </div>
                        </div>
                      </div>
                  </div>
                </div>           
              </li>
            </ul>
          </div>
        </main>
      </div>
    </div>
  </body>       
</template>

<script>
export default {
  name: "Projects",
  props: {
    msg: String,
  },
};
</script>
