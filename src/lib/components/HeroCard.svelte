<script>
  export let src;
  export let alt;
  export let text;
</script>

<div class="relative group overflow-hidden rounded-sm h-[400px] w-full">
  <img {src} {alt} class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
  <div class="absolute inset-0 bg-black/20 group-hover:bg-black/10 transition-colors"></div>
  <div class="absolute top-4 left-4 right-4">
    <p class="text-white text-sm font-medium leading-snug drop-shadow-md">{text}</p>
  </div>
</div>
