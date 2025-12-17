<script>
  import HeroCard from './HeroCard.svelte';
</script>

<section class="w-full px-6 pt-32 pb-20 flex flex-col items-center text-center">
  <span class="text-[#ff6b00] text-xs font-bold tracking-widest uppercase mb-6">Video Marketing for Hotels</span>
  
  <h1 class="text-white text-5xl md:text-6xl font-medium tracking-tight mb-6 max-w-4xl leading-[1.1]">
    Get more bookings with engaging videos every week
  </h1>
  
  <p class="text-gray-400 text-lg md:text-xl max-w-2xl mb-10 font-light leading-relaxed">
    Strana delivers seasonal, targeted, and channel-ready videos of your hotel every week, with no extra effort for you
  </p>
  
  <button class="bg-[#222] hover:bg-[#333] text-white px-6 py-3 rounded text-sm font-medium transition-colors border border-white/10 mb-20 flex items-center gap-2 group">
    Create Your First Video <span class="group-hover:translate-x-1 transition-transform">→</span>
  </button>

  <!-- Cards Grid -->
  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4 w-full max-w-[1400px] px-4">
    <HeroCard 
      src="https://images.unsplash.com/photo-1566073771259-6a8506099945?q=80&w=1000&auto=format&fit=crop" 
      alt="Hotel exterior" 
      text="This Munich hotel is a favourite among young couples" 
    />
    <HeroCard 
      src="https://images.unsplash.com/photo-1515934751635-c81c6bc9a2d8?q=80&w=1000&auto=format&fit=crop" 
      alt="Couple relaxing" 
      text="My kind of city trip" 
    />
    <HeroCard 
      src="https://images.unsplash.com/photo-1571896349842-6e53ce41e86a?q=80&w=1000&auto=format&fit=crop" 
      alt="Pool area" 
      text="This hotel is in Munich's most trendy neighbourhood" 
    />
    <HeroCard 
      src="https://images.unsplash.com/photo-1618773928121-c32242e63f39?q=80&w=1000&auto=format&fit=crop" 
      alt="Interior lounge" 
      text="POV: It's December and you woke up in Munich" 
    />
  </div>

  <!-- Platform Icons -->
  <div class="mt-16 flex flex-col items-center gap-4">
    <p class="text-gray-500 text-sm">Videos optimized for all travel-relevant platforms</p>
    <div class="flex items-center gap-3">
      <!-- Instagram Gradient -->
      <div class="w-8 h-8 rounded bg-gradient-to-tr from-yellow-400 via-red-500 to-purple-500 p-[1px]">
        <div class="w-full h-full border-2 border-white rounded flex items-center justify-center">
           <div class="w-3 h-3 border-2 border-white rounded-full"></div>
           <div class="absolute top-1.5 right-1.5 w-0.5 h-0.5 bg-white rounded-full"></div>
        </div>
        <!-- Simple SVG replacement for icons to ensure they look decent without external libs -->
        <svg viewBox="0 0 24 24" class="w-full h-full text-white fill-white p-1.5"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
      </div>
      
      <!-- TikTok -->
      <div class="w-8 h-8 rounded bg-black border border-gray-700 flex items-center justify-center">
        <svg viewBox="0 0 24 24" class="w-5 h-5 fill-white"><path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.46-.54 2.94-1.34 4.14-1.8 2.73-5.7 4.12-9.1 2.89-1.59-.58-3.03-1.52-4.1-2.79-3.03-3.64-1.8-9.24 2.86-10.96 1.4-.51 2.92-.55 4.38-.1v4.03c-.69-.25-1.44-.27-2.15-.05-1.56.48-2.58 2.03-2.34 3.65.23 1.55 1.68 2.67 3.25 2.51 1.54-.15 2.77-1.45 2.78-3V.02z"/></svg>
      </div>

      <!-- Booking.com (B.) -->
      <div class="w-8 h-8 rounded bg-[#003580] flex items-center justify-center">
        <span class="text-white font-bold text-lg">B.</span>
      </div>

      <!-- Expedia (Yellow Arrow) -->
      <div class="w-8 h-8 rounded bg-[#F9D916] flex items-center justify-center">
        <svg viewBox="0 0 24 24" class="w-5 h-5 fill-black rotate-[-45deg]"><path d="M21 12l-18 12v-24z"/></svg>
      </div>

      <!-- YouTube -->
      <div class="w-8 h-8 rounded bg-[#FF0000] flex items-center justify-center">
        <svg viewBox="0 0 24 24" class="w-5 h-5 fill-white"><path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/></svg>
      </div>
    </div>
  </div>
</section>
