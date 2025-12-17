<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import ProblemSection from "$lib/components/ProblemSection.svelte";
  import SolutionSection from "$lib/components/SolutionSection.svelte";
  import TestimonialSection from "$lib/components/TestimonialSection.svelte";
  import FeaturesSection from "$lib/components/FeaturesSection.svelte";
  import CTASection from "$lib/components/CTASection.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<main class="bg-[#0a0a0a] min-h-screen text-white font-sans selection:bg-orange-500/30">
  <Navbar />
  <Hero />
  <ProblemSection />
  <SolutionSection />
  <TestimonialSection />
  <FeaturesSection />
  <CTASection />
  <Footer />
</main>

