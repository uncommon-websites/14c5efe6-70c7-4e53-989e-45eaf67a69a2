<script lang="ts">
    export let theme: 'light' | 'dark' = 'light';
    let isMenuOpen = false;
</script>

<header class="fixed top-0 left-0 w-full z-50 px-6 py-5 transition-colors duration-300 {theme === 'dark' && !isMenuOpen ? 'text-white' : 'text-black bg-white/90 backdrop-blur-sm'}">
    <div class="flex justify-between items-center w-full max-w-[1400px] mx-auto relative">
        <!-- Left Navigation -->
        <nav class="hidden md:flex gap-8 text-[11px] font-medium tracking-wide uppercase">
            <a href="/" class="hover:opacity-60 transition-opacity">Technology</a>
            <a href="/" class="hover:opacity-60 transition-opacity">AIRMADE™ SAF</a>
            <a href="/" class="hover:opacity-60 transition-opacity">Defense</a>
            <a href="/" class="hover:opacity-60 transition-opacity">Company</a>
        </nav>

        <!-- Center Logo -->
        <div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 z-20">
            <a href="/" class="text-2xl font-bold tracking-tighter">AIRCO</a>
        </div>

        <!-- Right Placeholder -->
        <div class="w-[200px] hidden md:block"></div>
        
        <!-- Mobile Menu Button -->
        <button class="md:hidden ml-auto z-20 relative" on:click={() => isMenuOpen = !isMenuOpen}>
            {#if isMenuOpen}
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
                </svg>
            {:else}
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                </svg>
            {/if}
        </button>
    </div>

    <!-- Mobile Menu Overlay -->
    {#if isMenuOpen}
        <div class="fixed inset-0 bg-white z-10 flex flex-col items-center justify-center pt-20 pb-10 px-6 md:hidden">
            <nav class="flex flex-col items-center gap-8 text-lg font-medium tracking-wide uppercase">
                <a href="/" class="hover:opacity-60 transition-opacity" on:click={() => isMenuOpen = false}>Technology</a>
                <a href="/" class="hover:opacity-60 transition-opacity" on:click={() => isMenuOpen = false}>AIRMADE™ SAF</a>
                <a href="/" class="hover:opacity-60 transition-opacity" on:click={() => isMenuOpen = false}>Defense</a>
                <a href="/" class="hover:opacity-60 transition-opacity" on:click={() => isMenuOpen = false}>Company</a>
            </nav>
        </div>
    {/if}
</header>
