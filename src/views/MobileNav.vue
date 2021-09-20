<template>
    <div class="fixed w-full h-full top-24 right-0">
        <button type="button" aria-label="toggle modal" class="fixed w-full h-full cursor-auto focus:outline-none">
        </button>
        <nav class="fixed h-full mt-8">
            <div class="px-12 py-4">
                <a class="text-2xl font-medium text-gray-900 dark:text-gray-100"><router-link to="/">Home</router-link></a>
            </div>
            <div class="px-12 py-4">
                <a class="text-2xl font-medium text-gray-900 dark:text-gray-100"><router-link to="/projects">Projects</router-link></a>
            </div>
            <div class="px-12 py-4">
                <a class="text-2xl font-medium text-gray-900 dark:text-gray-100"><router-link to="/blog">Blog</router-link></a>
            </div>
        </nav>
    </div>
</template>
