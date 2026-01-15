<template>
    <div class="min-h-screen bg-gray-950 text-gray-200 font-sans selection:bg-purple-500 selection:text-white">

        <div class="max-w-6xl mx-auto px-6">

            <AppNavbar />

            <main class="py-10">
                <slot />
            </main>

            <footer class="py-10 text-center text-sm text-gray-500 border-t border-gray-800">
                © 2026 Ridho Portfolio
            </footer>

        </div>
    </div>
</template>