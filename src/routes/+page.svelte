<script lang="ts">
	import Header from "$lib/components/Header.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<Header />

<main class="pt-[72px]">
	<!-- Hero Section -->
	<section class="relative w-full h-[85vh] overflow-hidden">
		<img 
			src="https://images.unsplash.com/photo-1565610222536-ef125c59da2e?q=80&w=2070&auto=format&fit=crop" 
			alt="Industrial facility" 
			class="w-full h-full object-cover"
		/>
		<div class="absolute inset-0 bg-black/20 flex items-center justify-center">
			<h1 class="text-white text-5xl md:text-7xl font-normal tracking-tight">AIRMADE™ Technology</h1>
		</div>
	</section>

	<!-- Intro Text Section -->
	<section class="px-6 py-24 md:py-32 max-w-[1400px] mx-auto">
		<p class="text-lg mb-6">An Advanced Carbon Technology Platform</p>
		<h2 class="text-3xl md:text-[40px] leading-[1.15] font-normal max-w-4xl tracking-tight">
			AIRCO's proprietary AIRMADE™ Technology is an adaptable carbon conversion platform designed to enable industries to efficiently produce high-demand, fully-formulated synthetic fuels from carbon dioxide (CO₂) and hydrogen (H₂) where they are needed.
		</h2>
		<h2 class="text-3xl md:text-[40px] leading-[1.15] font-normal max-w-4xl mt-8 tracking-tight">
			Currently focused on fuel applications, AIRCO aims to deploy the most cost-effective and scalable fuel production technology available.
		</h2>
	</section>

	<!-- CTA Section -->
	<section class="px-6 pb-24 max-w-[1400px] mx-auto">
		<div class="bg-[#1a1a1a] text-white p-12 md:p-16 flex flex-col md:flex-row justify-between items-start md:items-center gap-8">
			<h3 class="text-2xl md:text-3xl font-normal max-w-md leading-tight">Learn how you can partner with AIRCO</h3>
			<button class="group flex items-center gap-2 px-6 py-2 border border-white/30 rounded-full hover:bg-white hover:text-black transition-colors text-sm">
				Contact Us
				<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 group-hover:translate-x-1 transition-transform">
					<path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3" />
				</svg>
			</button>
		</div>
	</section>

	<!-- Streamlined Process -->
	<section class="px-6 py-12 max-w-[1400px] mx-auto border-t border-gray-200">
		<div class="grid grid-cols-1 md:grid-cols-12 gap-12 mb-16 pt-4">
			<div class="md:col-span-4">
				<h3 class="text-3xl md:text-4xl font-normal tracking-tight">Streamlined Process</h3>
			</div>
			<div class="md:col-span-8 md:col-start-8">
				<p class="text-sm md:text-base leading-relaxed max-w-lg">
					We design our proprietary catalysts and reactors in-house, merging unit operations into a single streamlined process. This approach significantly boosts efficiency and allows us to tailor and scale our products to meet each customer's unique needs.
				</p>
			</div>
		</div>
		<div class="w-full aspect-video bg-gray-100 relative overflow-hidden">
			<img 
				src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?q=80&w=2070&auto=format&fit=crop" 
				alt="Lab equipment" 
				class="w-full h-full object-cover grayscale"
			/>
			<div class="absolute inset-0 flex items-center justify-center">
				<button class="w-16 h-16 bg-black/80 rounded-full flex items-center justify-center text-white hover:scale-110 transition-transform">
					<svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24" class="w-6 h-6 ml-1">
						<path d="M8 5v14l11-7z" />
					</svg>
				</button>
			</div>
		</div>
	</section>

	<!-- Scalable & Adaptable -->
	<section class="px-6 py-32 max-w-[1400px] mx-auto">
		<div class="text-center max-w-3xl mx-auto">
			<h3 class="text-4xl md:text-5xl font-normal mb-8 tracking-tight">Scalable & Adaptable</h3>
			<p class="text-lg md:text-xl leading-relaxed">
				AIRMADE™ Technology is built to enable scalable fuel production and seamless logistics, with the flexibility to deploy near end-users or within distribution networks. Designed for any location with access to CO₂ and H₂, it paves the way for the widespread adoption of AIRMADE® Fuel.
			</p>
		</div>
	</section>

	<!-- Feedstocks -->
	<section class="px-6 py-12 max-w-[1400px] mx-auto border-t border-gray-200">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-x-16 gap-y-12 pt-4">
			<!-- Title -->
			<div>
				<h3 class="text-3xl md:text-4xl font-normal tracking-tight">Feedstocks</h3>
			</div>
			
			<!-- Description -->
			<div>
				<p class="text-sm md:text-base leading-relaxed max-w-md">
					By using CO₂ as a feedstock to produce liquid fuels, AIRMADE™ Technology is designed to ensure a reliable and resilient energy supply chain. It helps reduce vulnerability to disruptions while strengthening energy security and domestic manufacturing, all while driving flexible and agile energy solutions.
				</p>
			</div>

			<!-- Image -->
			<div class="aspect-square bg-gray-100 overflow-hidden mt-8 md:mt-0">
				<img 
					src="https://images.unsplash.com/photo-1532601224476-15c79f2f7a51?q=80&w=2070&auto=format&fit=crop" 
					alt="Industrial tank" 
					class="w-full h-full object-cover grayscale"
				/>
			</div>

			<!-- List -->
			<div class="flex flex-col justify-end mt-8 md:mt-0">
				<div class="border-t border-gray-300 py-6">
					<h4 class="text-xl md:text-2xl font-normal">Waste Carbon Dioxide(CO₂)</h4>
				</div>
				<div class="border-t border-gray-300 py-6">
					<h4 class="text-xl md:text-2xl font-normal">Hydrogen(H₂)</h4>
				</div>
				<div class="border-t border-gray-300 py-6 border-b">
					<h4 class="text-xl md:text-2xl font-normal">Electricity</h4>
				</div>
			</div>
		</div>
	</section>

	<!-- Outputs -->
	<section class="px-6 py-12 max-w-[1400px] mx-auto border-t border-gray-200">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-x-16 gap-y-12 pt-4">
			<!-- Title -->
			<div>
				<h3 class="text-3xl md:text-4xl font-normal tracking-tight">Outputs</h3>
			</div>

			<!-- Description -->
			<div>
				<p class="text-sm md:text-base leading-relaxed max-w-md">
					After the feedstocks react with our catalysts, the resulting reactor liquid is processed through our proprietary separation system, producing distinct liquid hydrocarbons, also referred to as liquid fuels.
				</p>
			</div>

			<!-- Image -->
			<div class="aspect-square bg-gray-100 overflow-hidden mt-8 md:mt-0">
				<img 
					src="https://images.unsplash.com/photo-1617791160505-6f00504e3519?q=80&w=2000&auto=format&fit=crop" 
					alt="Metal component" 
					class="w-full h-full object-cover grayscale"
				/>
			</div>

			<!-- List -->
			<div class="flex flex-col justify-end mt-8 md:mt-0">
				<div class="border-t border-gray-300 py-6">
					<h4 class="text-xl md:text-2xl font-normal">SAF</h4>
				</div>
				<div class="border-t border-gray-300 py-6">
					<h4 class="text-xl md:text-2xl font-normal">Diesel</h4>
				</div>
				<div class="border-t border-gray-300 py-6 border-b">
					<h4 class="text-xl md:text-2xl font-normal">Gasoline</h4>
				</div>
			</div>
		</div>
	</section>

	<!-- Catalyst -->
	<section class="px-6 py-12 max-w-[1400px] mx-auto border-t border-gray-200">
		<div class="grid grid-cols-1 md:grid-cols-12 gap-12 mb-16 pt-4">
			<div class="md:col-span-4">
				<h3 class="text-3xl md:text-4xl font-normal tracking-tight">Catalyst</h3>
			</div>
			<div class="md:col-span-8 md:col-start-8">
				<p class="text-sm md:text-base leading-relaxed max-w-lg">
					Our catalyst plays the most central role in our process. Made from non-toxic, non-rare Earth minerals, our catalyst helps facilitate the chemical reaction between CO₂ and H₂ inside our reactor.
				</p>
			</div>
		</div>
		<div class="w-full h-[600px] bg-blue-900 relative overflow-hidden">
			<img 
				src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?q=80&w=1974&auto=format&fit=crop" 
				alt="Microscopic view" 
				class="w-full h-full object-cover"
			/>
		</div>
	</section>

	<!-- Bottom Hero -->
	<section class="relative w-full h-[85vh] overflow-hidden">
		<img 
			src="https://images.unsplash.com/photo-1464037866556-6812c9d1c72e?q=80&w=2070&auto=format&fit=crop" 
			alt="Cloudy landscape" 
			class="w-full h-full object-cover grayscale"
		/>
		<div class="absolute bottom-0 left-0 p-6 md:p-12 w-full max-w-[1400px] mx-auto left-0 right-0">
			<h2 class="text-white text-5xl md:text-6xl font-normal tracking-tight mb-2">AIRMADE® SAF</h2>
			<p class="text-white/80 text-lg md:text-xl">Fully-Formulated Jet Fuel Made from CO₂</p>
			<button class="mt-6 px-6 py-2 bg-white/10 backdrop-blur-md border border-white/30 text-white rounded-full hover:bg-white hover:text-black transition-colors text-sm">
				Learn More
			</button>
		</div>
	</section>
</main>

<Footer />

