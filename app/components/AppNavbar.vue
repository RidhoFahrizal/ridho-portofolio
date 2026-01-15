<script setup>
const links = [
    { name: 'Home', path: '/' },
    { name: 'Project', path: '/project' },
    { name: 'Profile', path: '/profile' },
];
</script>

<template>
    <nav class="flex items-center justify-center px-12 py-4 ">

        <div class="flex gap-4">
            <NuxtLink v-for="link in links" :key="link.path" :to="link.path" class="px-4 py-2 transition-all duration-300
                hover:bg-[#B3ABAB] text-black">
                {{ link.name }}
            </NuxtLink>
        </div>
    </nav>
</template>