<template>
  <body class="antialiased bg-gray-900 text-white">
    <div class="max-w-3xl px-4 mx-auto sm:px-6 xl:max-w-5xl xl:px-0">
      <div class="flex flex-col justify-between h-screen">
        <main class="mb-auto">
          <div class="divide-y divide-gray-200 dark:divide-gray-700">
            <div class="pt-6 pb-8 space-y-2 md:space-y-5">
              <h1 class="text-3xl font-extrabold leading-9 tracking-tight text-gray-900 dark:text-gray-100 sm:text-4xl sm:leading-10 md:text-6xl md:leading-14">Projects</h1>
            </div>
            <ul class="ulc divide-y divide-gray-200 dark:divide-gray-700">
                <li class="py-12">

                  <div class="flex flex-wrap">

                    <!-- Column -->

                    <div class="rounded-lg px-1 w-full md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3">
                      <div class="projects" id="work_section">
                        <a href="https://github.com/brandonsaldan/fox" target="_blank">
                        <section>
                        <div class="section_title">fox</div>
                          <div class="about_section">
                            <span style="display:block;">🦊 social media username scraping discord bot</span>
                          </div>
                        </section>
                        </a>
                      </div>
                    </div>

                    <div class="rounded-lg w-full md:w-1/2 lg:w-1/2">
                      <div class="projects" id="work_section">
                        <a href="https://github.com/brandonsaldan/atlas" target="_blank">
                        <section>
                        <div class="section_title">atlas</div>
                          <div class="about_section">
                            <span style="display:block;">📰 personal website built with vue.js and tailwind</span>
                          </div>
                        </section>
                        </a>
                      </div>
                    </div>

                    <div class="rounded-lg w-full md:w-1/2 lg:w-1/3">
                      <div class="projects" id="work_section">
                        <a href="https://github.com/brandonsaldan/ticker" target="_blank">
                        <section>
                        <div class="section_title">ticker</div>
                          <div class="about_section">
                            <span style="display:block;">💸 stock and cryptocurrency discord bot</span>
                          </div>
                        </section>
                        </a>
                      </div>
                    </div>

                    <div class="rounded-lg w-full md:w-1/2 lg:w-1/3">
                      <div class="projects" id="work_section">
                        <a href="https://github.com/brandonsaldan/mockingbird" target="_blank">
                        <section>
                        <div class="section_title">mockingbird</div>
                          <div class="about_section">
                            <span style="display:block;">🐦tweet tweet (watch this space, coming soon)</span>
                          </div>
                        </section>
                        </a>
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
