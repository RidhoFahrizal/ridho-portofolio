<template>
    <div
        class="flex flex-col min-h-screen bg-[#E6DADA] text-black font-sans selection:bg-purple-500 selection:text-black overflow-x-hidden">

        <div class="w-full max-w-screen-sm mx-auto flex-grow flex flex-col px-4">

            <AppNavbar />

            <main class="flex-grow py-10">
                <slot />
            </main>

            <footer class="py-10 text-center text-md text-black border-t border-black">
                © 2026 Ridho Portfolio
            </footer>
        </div>

       
    </div>
</template>