<template>
  <body class="antialiased bg-gray-900 text-white">
    <div class="max-w-3xl px-4 mx-auto sm:px-6 xl:max-w-5xl xl:px-0">
      <div class="flex flex-col justify-between h-screen">
        <main class="mb-auto">
          <div class="divide-y divide-gray-200 dark:divide-gray-700 animate__animated animate__fadeIn">
            <div class="pt-6 pb-8 space-y-2 md:space-y-5">
              <h1 class="text-3xl font-extrabold leading-9 tracking-tight text-gray-900 dark:text-gray-100 sm:text-4xl sm:leading-10 md:text-6xl md:leading-14">Blog</h1>
            </div>
            <ul class="divide-y divide-gray-200 dark:divide-gray-700">
                <li class="py-12">
                  <article>
                    <div class="space-y-2 xl:grid xl:grid-cols-4 xl:space-y-0 xl:items-baseline">
                      <div class="space-y-5 xl:col-span-3">
                        <div class="space-y-6">
                          <div>
                            <h2>
                              <p class="text-lg leading-7 text-gray-500 dark:text-gray-400">No posts yet, check again later!</p>
                            </h2>
                          </div>
                        </div>
                      </div>
                    </div>
                  </article>
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
  name: "Blog",
  props: {
    msg: String,
  },
};
</script>
