<script setup>
const links = [
    { name: 'Home', path: '/' },
    { name: 'Portfolio', path: '/portfolio' },
    { name: 'Profile', path: '/profile' },
];
</script>

<template>
    <nav class="flex items-center justify-center px-12 py-4 ">

        <div class="flex gap-4">
            <NuxtLink v-for="link in links" :key="link.path" :to="link.path" class="px-4 py-2 rounded-lg transition-all duration-300
               hover:text-black hover:bg-white ">
                {{ link.name }}
            </NuxtLink>
        </div>
    </nav>
</template>