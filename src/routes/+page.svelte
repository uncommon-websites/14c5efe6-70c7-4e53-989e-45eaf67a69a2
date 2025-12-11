<script lang="ts">
	import Header from "$lib/components/Header.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<Header />

<main class="pt-[72px]">
	<!-- Hero Section -->

	<!-- Site OS Platform -->
	<section class="px-6 py-12 max-w-[1400px] mx-auto mt-16 border-gray-200">
		<div class="grid grid-cols-1 md:grid-cols-12 gap-12 mb-16 pt-4">
			<div class="md:col-span-4">
				<h3 class="text-3xl md:text-4xl font-normal tracking-tight">Forge</h3>
			</div>
			<div class="md:col-span-8 md:col-start-8">
				<p class="text-sm md:text-base leading-relaxed max-w-lg">
					Our operational intelligence platform serves as a single source of truth for your entire site. Real-time monitoring, customizable zones, and direct updates to deployed systems enable unprecedented visibility and control over your operations.
				</p>
			</div>
		</div>
		<div class="w-full aspect-video bg-gray-100 relative overflow-hidden">
			<img 
				src="/generated/image-wide-view-of-active-quarry-site-with-mul-1765438537081-2.webp" 
				alt="Quarry site operations" 
				class="w-full h-full object-cover"
			/>
		</div>
	</section>

	<!-- Intro Text Section -->
	<section class="px-6 py-24 md:py-32 max-w-[1400px] mx-auto">
		<p class="text-lg mb-6">Vision Language Action Models for Heavy Machinery</p>
		<h2 class="text-3xl md:text-[40px] leading-[1.15] font-normal max-w-4xl tracking-tight">
			Forge transforms the world's largest off-highway machinery into intelligent autonomous systems through end-to-end learning and embodied AI.
		</h2>
		<h2 class="text-3xl md:text-[40px] leading-[1.15] font-normal max-w-4xl mt-8 tracking-tight">
			Starting with mining loaders, we're capturing the $180B off-highway market by making machines that think, adapt, and perform with human-like intelligence.
		</h2>
	</section>




	<!-- Safety First -->
	<section class="px-6 py-32 max-w-[1400px] mx-auto">
		<div class="text-center max-w-3xl mx-auto">
			<h3 class="text-4xl md:text-5xl font-normal mb-8 tracking-tight">Safety First, Always</h3>
			<p class="text-lg md:text-xl leading-relaxed">
				Every feature is built to solve real customer problems. Our systems prevent Lost Time Injuries, eliminate costly collisions, and reduce downtime by up to 30%. Safety isn't just a priority—it's embedded in every design decision and line of code.
			</p>
		</div>
	</section>

	<!-- Machine Assist -->
	<section class="px-6 py-12 max-w-[1400px] mx-auto border-t border-gray-200">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-x-16 gap-y-12 pt-4">
			<!-- Title -->
			<div>
				<h3 class="text-3xl md:text-4xl font-normal tracking-tight">Machine Assist</h3>
			</div>
			
			<!-- Description -->
			<div>
				<p class="text-sm md:text-base leading-relaxed max-w-md">
					Advanced collision avoidance and operator assistance systems that enhance safety and productivity. Our technology provides real-time warnings, precision data, and seamless driver interaction to prevent accidents and optimize performance.
				</p>
			</div>

			<!-- Image -->
			<div class="aspect-square bg-gray-100 overflow-hidden mt-8 md:mt-0">
				<img 
					src="/generated/image-mining-equipment-operator-in-safety-gear-1765438534782-1.webp" 
					alt="Operator in loader cabin" 
					class="w-full h-full object-cover"
				/>
			</div>

			<!-- List -->
			<div class="flex flex-col justify-end mt-8 md:mt-0">
				<div class="border-t border-gray-300 py-6">
					<h4 class="text-xl md:text-2xl font-normal">Collision Warnings</h4>
				</div>
				<div class="border-t border-gray-300 py-6">
					<h4 class="text-xl md:text-2xl font-normal">Precision Data</h4>
				</div>
				<div class="border-t border-gray-300 py-6 border-b">
					<h4 class="text-xl md:text-2xl font-normal">Driver Interaction</h4>
				</div>
			</div>
		</div>
	</section>

	<!-- Customer Results -->
	<section class="px-6 py-12 max-w-[1400px] mx-auto border-t border-gray-200">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-x-16 gap-y-12 pt-4">
			<!-- Title -->
			<div>
				<h3 class="text-3xl md:text-4xl font-normal tracking-tight">Proven Results</h3>
			</div>

			<!-- Description -->
			<div>
				<p class="text-sm md:text-base leading-relaxed max-w-md">
					Our customers see measurable improvements from day one. CEMEX and Lhoist have equipped entire sites with Forge technology, achieving significant reductions in downtime and preventing costly accidents.
				</p>
			</div>

			<!-- Image -->
			<div class="aspect-square bg-gray-100 overflow-hidden mt-8 md:mt-0">
				<img 
					src="/generated/image-close-up-of-heavy-machinery-wheels-and-u-1765438539470-3.webp" 
					alt="Heavy machinery detail" 
					class="w-full h-full object-cover"
				/>
			</div>

			<!-- List -->
			<div class="flex flex-col justify-end mt-8 md:mt-0">
				<div class="border-t border-gray-300 py-6">
					<h4 class="text-xl md:text-2xl font-normal">30% Downtime Reduction</h4>
				</div>
				<div class="border-t border-gray-300 py-6">
					<h4 class="text-xl md:text-2xl font-normal">Zero Lost Time Injuries</h4>
				</div>
				<div class="border-t border-gray-300 py-6 border-b">
					<h4 class="text-xl md:text-2xl font-normal">Eliminated Collisions</h4>
				</div>
			</div>
		</div>
	</section>

	<!-- Field-First Approach -->
	<section class="px-6 py-12 max-w-[1400px] mx-auto border-t border-gray-200">
		<div class="grid grid-cols-1 md:grid-cols-12 gap-12 mb-16 pt-4">
			<div class="md:col-span-4">
				<h3 class="text-3xl md:text-4xl font-normal tracking-tight">Built in the Field</h3>
			</div>
			<div class="md:col-span-8 md:col-start-8">
				<p class="text-sm md:text-base leading-relaxed max-w-lg">
					We're not afraid of muddy boots, tough deadlines, or complex AI tasks. Our team deploys directly to mine sites, testing and refining our systems in the most demanding real-world conditions. This hands-on approach ensures our technology works where it matters most.
				</p>
			</div>
		</div>
		<div class="w-full h-[600px] bg-gray-900 relative overflow-hidden">
			<img 
				src="/generated/image-engineers-with-laptops-and-tablets-at-mi-1765438541836-4.webp" 
				alt="Engineers testing at mine site" 
				class="w-full h-full object-cover"
			/>
		</div>
	</section>

	<!-- Customer Testimonials -->
	<section class="px-6 py-24 max-w-[1400px] mx-auto border-t border-gray-200">
		<h3 class="text-3xl md:text-4xl font-normal tracking-tight mb-16">Trusted by Industry Leaders</h3>
		<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
			<!-- CEMEX Testimonial -->
			<div class="border-l-2 border-gray-900 pl-8">
				<p class="text-lg md:text-xl leading-relaxed mb-6 italic">
					"We've had a multi-year relationship with Forge. Our entire site is now equipped with their technology, and the impact on safety and operations has been remarkable."
				</p>
				<div class="text-sm">
					<p class="font-medium">Thomas Weber</p>
					<p class="text-gray-600">Head of Quarry Operations, Rüdersdorf</p>
					<p class="text-gray-900 font-medium mt-1">CEMEX</p>
				</div>
			</div>

			<!-- Lhoist Testimonial -->
			<div class="border-l-2 border-gray-900 pl-8">
				<p class="text-lg md:text-xl leading-relaxed mb-6 italic">
					"Site OS and Machine Assist have transformed how we operate. The collision warnings and precision data give us confidence, and the driver interaction is seamless."
				</p>
				<div class="text-sm">
					<p class="font-medium">Nicolai Hecker</p>
					<p class="text-gray-600">Department for Extraction, Flandersbach</p>
					<p class="text-gray-900 font-medium mt-1">Lhoist</p>
				</div>
			</div>
		</div>
	</section>

	<!-- Bottom Hero -->
	<section class="relative w-full h-[85vh] overflow-hidden">
		<img 
			src="/generated/image-autonomous-mining-loader-moving-material-1765438544066-5.webp" 
			alt="Autonomous mining loader" 
			class="w-full h-full object-cover"
		/>
		<div class="absolute bottom-0 left-0 p-6 md:p-12 w-full max-w-[1400px] mx-auto left-0 right-0">
			<h2 class="text-white text-5xl md:text-6xl font-normal tracking-tight mb-2">The Future is Autonomous</h2>
			<p class="text-white/80 text-lg md:text-xl">Vision Language Action Models for Off-Highway Equipment</p>
			<button class="mt-6 px-6 py-2 bg-white/10 backdrop-blur-md border border-white/30 text-white rounded-full hover:bg-white hover:text-black transition-colors text-sm">
				See It In Action
			</button>
		</div>
	</section>
</main>

<Footer />

