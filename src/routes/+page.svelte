<script lang="ts">
  import { onMount } from 'svelte';

  // No external scripts needed for now
</script>

<div class="w-full overflow-x-hidden bg-sunrise-beige font-body selection:bg-sunrise-orange selection:text-white">
  <!-- Hero Section -->
  <section class="relative min-h-[90vh] flex flex-col items-center justify-center pt-20 pb-32 px-6 md:px-12">
    <!-- Logo (Top Left) -->
    <div class="absolute top-8 left-6 md:top-10 md:left-10">
      <svg width="48" height="24" viewBox="0 0 48 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <circle cx="10" cy="12" r="6" fill="#FF573E"/>
        <line x1="10" y1="12" x2="48" y2="12" stroke="#FF573E" stroke-width="2"/>
      </svg>
    </div>

    <!-- Main Graphic -->
    <div class="mb-16 md:mb-24">
      <div class="w-40 h-40 md:w-56 md:h-56 bg-sunrise-orange rounded-full"></div>
    </div>

    <!-- Hero Text -->
    <div class="max-w-[1000px] text-left md:text-center mx-auto">
      <h1 class="text-2xl md:text-[2.75rem] leading-[1.2] font-normal tracking-tight text-sunrise-black">
        <span class="text-sunrise-orange">Sunrise is a new kind of robotics company.</span>
        We don’t just build robots — we shape the future of manufacturing. Our
        <span class="text-sunrise-orange">intelligent, autonomous robotic cells</span>
        transform existing manufacturing processes, effortlessly scale capacity, and
        <span class="text-sunrise-orange">empower manufacturers</span>
        to redeploy their operators to the most valuable tasks.
      </h1>
    </div>
  </section>

  <!-- Mission Section -->
  <section class="relative bg-sunrise-orange text-white py-24 px-6 md:px-12 overflow-hidden">
    <!-- Background Graphic -->
    <div class="absolute top-0 left-0 w-full h-full pointer-events-none overflow-hidden">
       <!-- Large thin white circle outline -->
       <div class="absolute -left-[10%] -top-[10%] w-[60vw] h-[60vw] rounded-full border border-white/40"></div>
    </div>

    <div class="relative z-10 grid grid-cols-1 lg:grid-cols-2 gap-16">
      <div class="flex flex-col justify-start h-full">
        <span class="text-[10px] font-bold tracking-[0.2em] uppercase mb-8 md:mb-16">Mission</span>
        <h2 class="text-4xl md:text-6xl lg:text-[4.5rem] font-normal leading-[1.05] tracking-tight max-w-xl">
          Sunrise is on a mission to augment humanity through intelligent robotics.
        </h2>
      </div>
      
      <div class="flex flex-col justify-end items-start lg:pl-24 pb-4">
        <p class="text-sm md:text-[0.95rem] leading-relaxed mb-12 opacity-90 max-w-[460px]">
          We’re starting with industrial manufacturing, a key catalyst of human progress. Everything we touch and use in our daily lives is manufactured, yet the industry and our economies face growing challenges—labor shortages, the need for greater flexibility, and rising supply chain risks.
        </p>
        <button class="px-6 py-2 border border-white rounded-full text-xs font-medium hover:bg-white hover:text-sunrise-orange transition-colors uppercase tracking-wide">
          Read more
        </button>
      </div>
    </div>
  </section>

  <!-- Product Section -->
  <section class="relative py-24 px-6 md:px-12 bg-sunrise-beige">
    <!-- Top Graphic: Dotted Arc -->
    <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full max-w-3xl flex justify-center">
       <svg width="600" height="150" viewBox="0 0 600 150" fill="none" class="opacity-60">
         <path d="M0,150 Q300,-50 600,150" stroke="white" stroke-width="6" stroke-dasharray="0 20" stroke-linecap="round"/>
       </svg>
    </div>

    <div class="mb-24 mt-12">
      <span class="text-[10px] font-bold tracking-[0.2em] uppercase text-gray-400 block mb-8">Product</span>
      <h2 class="text-5xl md:text-[5.5rem] font-normal leading-[0.95] tracking-tight text-sunrise-black">
        Intelligence.<br>
        Flexibility.<br>
        Scalability.
      </h2>
    </div>

    <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
      <!-- Feature List -->
      <div class="lg:col-span-5 space-y-0 border-t border-gray-300">
        <div class="py-6 border-b border-gray-300 group cursor-pointer">
          <h3 class="text-lg font-medium mb-3 text-sunrise-black">Built-In Perception</h3>
          <p class="text-[13px] text-sunrise-black leading-relaxed max-w-md">
            Each Sunrise cell has a complete view and understanding of its work area and surroundings. This allows for unprecedented operational capabilities and operation in work environments designed for people, not machines.
          </p>
        </div>
        <div class="py-6 border-b border-gray-300 text-gray-400 hover:text-sunrise-black transition-colors cursor-pointer flex justify-between items-center group">
          <h3 class="text-lg font-normal">Human-like Coordination. Industrial Strength</h3>
        </div>
        <div class="py-6 border-b border-gray-300 text-gray-400 hover:text-sunrise-black transition-colors cursor-pointer group">
          <h3 class="text-lg font-normal">Driven by Artificial Intelligence</h3>
        </div>
        <div class="py-6 border-b border-gray-300 text-gray-400 hover:text-sunrise-black transition-colors cursor-pointer group">
          <h3 class="text-lg font-normal">Flexible by Design</h3>
        </div>
        <div class="py-6 border-b border-gray-300 text-gray-400 hover:text-sunrise-black transition-colors cursor-pointer group">
          <h3 class="text-lg font-normal">Safe and Sound</h3>
        </div>
        <div class="py-6 border-b border-gray-300 text-gray-400 hover:text-sunrise-black transition-colors cursor-pointer group">
          <h3 class="text-lg font-normal">Plug and Play. Literally</h3>
        </div>
      </div>

      <!-- Product Image Placeholder -->
      <div class="lg:col-span-7 relative h-[700px] w-full flex items-center justify-center lg:justify-end">
        <!-- Booth CSS Representation -->
        <div class="relative w-full max-w-[500px] aspect-[0.7] perspective-1000">
           <!-- The Booth Container -->
           <div class="relative w-full h-full bg-gradient-to-b from-gray-50 to-white rounded-[40px] shadow-2xl overflow-hidden border border-white flex flex-col">
              
              <!-- Top Header (Dark) -->
              <div class="h-16 bg-[#2A2A2A] w-full flex items-center justify-center relative z-20">
                  <div class="w-1/3 h-1 bg-gray-600 rounded-full"></div>
              </div>

              <!-- Interior (Glass & Robot) -->
              <div class="flex-1 relative bg-gradient-to-b from-[#E0E0E0] to-[#F5F5F5] overflow-hidden">
                  <!-- Back Wall Grid -->
                  <div class="absolute inset-0 opacity-10" 
                       style="background-image: radial-gradient(#000 1px, transparent 1px); background-size: 20px 20px;">
                  </div>

                  <!-- Lighting Effect -->
                  <div class="absolute top-0 left-1/2 -translate-x-1/2 w-3/4 h-32 bg-white opacity-20 blur-2xl rounded-full pointer-events-none"></div>

                  <!-- Robot Arm (Abstract) -->
                  <div class="absolute bottom-32 left-1/2 -translate-x-1/2 w-40 h-80 flex flex-col items-center justify-end z-10">
                      <!-- Arm segments -->
                      <div class="w-24 h-32 bg-white border border-gray-200 rounded-2xl shadow-lg relative mb-[-10px] z-20 flex items-center justify-center">
                          <div class="w-16 h-16 rounded-full border border-gray-100"></div>
                      </div>
                      <div class="w-6 h-24 bg-gray-300 rounded-full -rotate-12 origin-bottom mb-[-10px] z-10"></div>
                      <div class="w-32 h-8 bg-gray-800 rounded-full z-30 shadow-xl"></div>
                  </div>

                  <!-- Glass Reflection Overlay -->
                  <div class="absolute inset-0 bg-gradient-to-tr from-transparent via-white/20 to-transparent pointer-events-none"></div>
              </div>

              <!-- Bottom Base (White) -->
              <div class="h-32 bg-white w-full border-t border-gray-100 relative z-20 flex items-center justify-center">
                  <div class="w-12 h-12 rounded-full border border-gray-200 flex items-center justify-center shadow-inner">
                      <div class="w-2 h-2 bg-black rounded-full"></div>
                  </div>
              </div>
           </div>
           
           <!-- Shadow -->
           <div class="absolute -bottom-10 left-1/2 -translate-x-1/2 w-3/4 h-10 bg-black/20 blur-2xl rounded-full"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Grid -->
  <section class="py-24 px-6 md:px-12 bg-sunrise-beige border-t border-gray-200">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-x-12 gap-y-16">
      <!-- Feature 1 -->
      <div class="flex flex-col h-full">
        <h3 class="text-2xl font-normal mb-6">See. Think. Act.</h3>
        <p class="text-[13px] text-gray-600 mb-12 leading-relaxed">
          Continuously observing the environment, interpreting what it sees with advanced AI, and executing processes autonomously—all in real time. Sunrise’s fleet learns from each cycle, adapting to new insights and delivering unmatched performance on the facility floor.
        </p>
        <div class="mt-auto flex justify-center py-8">
           <svg width="180" height="180" viewBox="0 0 180 180" fill="none">
             <!-- Outer Circle -->
             <circle cx="90" cy="90" r="89" stroke="#111" stroke-width="0.8"/>
             <!-- Inner Circle -->
             <circle cx="90" cy="90" r="30" stroke="#111" stroke-width="0.8"/>
             <!-- Dot on outer circle (bottom leftish) -->
             <circle cx="27" cy="115" r="3.5" fill="#111"/>
           </svg>
        </div>
      </div>

      <!-- Feature 2 -->
      <div class="flex flex-col h-full">
        <h3 class="text-2xl font-normal mb-6">Get the Job Done</h3>
        <p class="text-[13px] text-gray-600 mb-12 leading-relaxed">
          Built for flexibility. Each unit can be quickly retrained to handle process variations and new tasks with minimal downtime. Our design and business model ensures that your operations remain agile and future-ready—no matter what comes next.
        </p>
        <div class="mt-auto flex justify-center py-8">
           <svg width="180" height="180" viewBox="0 0 180 180" fill="none">
             <!-- Outer Circle -->
             <circle cx="90" cy="90" r="89" stroke="#111" stroke-width="0.8"/>
             <!-- Middle Circle -->
             <circle cx="90" cy="90" r="60" stroke="#111" stroke-width="0.8"/>
             <!-- Inner Circle -->
             <circle cx="90" cy="90" r="30" stroke="#111" stroke-width="0.8"/>
             <!-- Dot on middle circle -->
             <circle cx="48" cy="132" r="3.5" fill="#111"/>
           </svg>
        </div>
      </div>

      <!-- Feature 3 -->
      <div class="flex flex-col h-full">
        <h3 class="text-2xl font-normal mb-6">Grow on Demand</h3>
        <p class="text-[13px] text-gray-600 mb-12 leading-relaxed">
          Add capacity whenever you need it—without the burden of heavy setup costs or capital investments. With a rapidly deployable fleet, you can scale your operations in step with your biggest ambitions.
        </p>
        <div class="mt-auto flex justify-center py-8">
           <svg width="180" height="180" viewBox="0 0 180 180" fill="none">
             <!-- Outer Circle -->
             <circle cx="90" cy="90" r="89" stroke="#111" stroke-width="0.8"/>
             <!-- Dotted Inner Circle -->
             <circle cx="90" cy="90" r="50" stroke="#111" stroke-width="0.8" stroke-dasharray="3 3"/>
             <!-- Dot on dotted circle -->
             <circle cx="55" cy="125" r="3.5" fill="#111"/>
           </svg>
        </div>
      </div>
    </div>
  </section>

  <!-- Dark Section -->
  <section class="bg-sunrise-dark text-white py-32 px-6 md:px-12 relative overflow-hidden">
    <!-- Background Graphic -->
    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full h-full pointer-events-none flex items-center justify-center opacity-40">
       <svg width="1000" height="500" viewBox="0 0 1000 500" fill="none">
         <!-- Left Circle -->
         <circle cx="350" cy="250" r="200" stroke="white" stroke-width="0.8" stroke-dasharray="4 4"/>
         <!-- Right Circle -->
         <circle cx="650" cy="250" r="200" stroke="white" stroke-width="0.8" stroke-dasharray="4 4"/>
         <!-- Connecting Line -->
         <line x1="150" y1="250" x2="850" y2="250" stroke="white" stroke-width="0.8" stroke-dasharray="4 4"/>
         <!-- Dots -->
         <circle cx="150" cy="250" r="4" fill="white"/>
         <circle cx="850" cy="250" r="4" fill="white"/>
       </svg>
    </div>

    <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center relative z-10">
      <div>
        <div class="flex items-center mb-8">
           <!-- Small icon -->
           <svg width="28" height="28" viewBox="0 0 24 24" fill="none" class="mr-4">
             <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z" fill="#fff"/>
             <path d="M2 12h20" stroke="#545469" stroke-width="1.5"/>
           </svg>
        </div>
        <h2 class="text-4xl md:text-[3.5rem] font-normal leading-tight tracking-tight">
          Intelligent Software.<br>
          Autonomous<br>
          Hardware.
        </h2>
      </div>

      <div class="flex flex-col items-start lg:pl-24">
        <p class="text-sm md:text-[0.95rem] leading-relaxed mb-8 opacity-90 max-w-[460px]">
          At Sunrise, we’ve designed and developed a unique hardware platform of robotic cells, trained in simulation and deployed as an ever-learning, continuously improving autonomous fleet.
        </p>
        <p class="text-sm md:text-[0.95rem] leading-relaxed mb-12 opacity-90 max-w-[460px]">
          Each cell is designed for versatility, easily repurposed to meet a variety of manufacturing needs. By uniting hardware and software into one holistic system, we unlock unprecedented flexibility and efficiency for a wide range of operations.
        </p>
        <button class="px-6 py-2 border border-white rounded-full text-xs font-medium hover:bg-white hover:text-sunrise-dark transition-colors uppercase tracking-wide">
          Get more information
        </button>
      </div>
    </div>
  </section>

  <!-- Careers Section -->
  <section class="py-24 px-6 md:px-12 bg-sunrise-beige relative overflow-hidden">
    <div class="absolute top-0 left-0 w-full h-full pointer-events-none">
       <!-- Large Orange Outline Circles forming an 8 or infinity shape -->
       <svg class="absolute -left-[10%] top-0 w-[50vw] h-[100%]" viewBox="0 0 400 800" fill="none" preserveAspectRatio="xMidYMid slice">
         <circle cx="200" cy="200" r="199" stroke="#FF573E" stroke-width="0.8"/>
         <circle cx="200" cy="600" r="199" stroke="#FF573E" stroke-width="0.8"/>
       </svg>
    </div>

    <div class="relative z-10">
      <span class="text-[10px] font-bold tracking-[0.2em] uppercase text-gray-400 block mb-24">Careers</span>
      
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-16">
        <h2 class="text-5xl md:text-[4.5rem] font-normal text-sunrise-black leading-none tracking-tight">
          Join the Mission
        </h2>
        
        <div class="flex flex-col items-start lg:pl-24 pt-2">
          <p class="text-sm md:text-[0.95rem] leading-relaxed mb-8 text-sunrise-black max-w-[460px]">
            We are a team of engineers, scientists, roboticists, designers and company builders developing technology, designing and engineering products that power intelligent robotics of today towards the general embodied intelligence of the future.
          </p>
          <p class="text-sm md:text-[0.95rem] leading-relaxed mb-12 text-sunrise-black max-w-[460px]">
            The Sunrise team has previously built drones that could lift humans, delivered robotics systems for automotive industry, helped produce over 100M consumer electronics products, and developed software platforms serving 150M+ users daily.
          </p>
          <button class="px-6 py-2 border border-sunrise-black rounded-full text-xs font-medium hover:bg-sunrise-black hover:text-white transition-colors uppercase tracking-wide">
            Open Positions
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-sunrise-beige border-t border-gray-300 py-16 px-6 md:px-12 text-[11px] text-gray-500 font-medium">
    <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
      <div class="col-span-1">
        <span class="text-sunrise-orange font-bold tracking-[0.15em] uppercase">Sunrise</span>
      </div>
      
      <div class="col-span-1 md:col-span-2 flex flex-col md:flex-row gap-4 md:gap-12 text-sunrise-black">
        <a href="#" class="hover:text-sunrise-orange transition-colors">Contact</a>
        <a href="#" class="hover:text-sunrise-orange transition-colors">Media Assets</a>
        <a href="#" class="hover:text-sunrise-orange transition-colors">About</a>
        <a href="#" class="hover:text-sunrise-orange transition-colors">Careers</a>
      </div>
      
      <div class="col-span-1 flex justify-between md:justify-end gap-8">
         <span class="cursor-pointer hover:text-sunrise-black transition-colors">Privacy & Legal</span>
      </div>
    </div>
    
    <div class="mt-16">
      <span>© 2025 Sunrise Robotics</span>
    </div>
  </footer>
</div>

<style>
  /* Ensure smooth rendering */
  :global(body) {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
</style>

