[The Overlap - Honest Rebuild Homepage.html](https://github.com/user-attachments/files/29996496/The.Overlap.-.Honest.Rebuild.Homepage.html)
==rebuilding in public...
or maybe continuing to fail in public==


### *I BUILT TWO SEVEN-FIGURE BUSINESSES.* 
### *THEN I LOST EVERYTHING.*

I was an insecure kid who found success. Maybe I overcompensated.
Now I'm broke, frustrated, and figuring out who I actually am.

> I had one of the most successfull online music production businesses (Legion Beats). 
> Made millions. 
> Got hated. 
> Got praised. 
> Couldn't tell which was real. 
> Lost it all.

Now I sit at the same computer where money used to come to me. And nothing. 
Some days I hate myself. Some days I'm learning. 
Most days it's both. 
But I still know things. 
This is The Overlap: what I learned when I had it, what I'm learning now that I don't.

Subscribe to The Overlap
NO BULLSHIT. NO GURUS. JUST WHAT'S REAL.


# Optin Page Built

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Overlap - Music, Marketing, & AI Rebuild</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://code.iconify.design/iconify-icon/1.0.7/iconify-icon.min.js"></script>
  <link href="https://api.fontshare.com/v2/css?f[]=anton@400&f[]=satoshi@400,500,700&display=swap" rel="stylesheet">
  <style>
    :root {
      --charcoal: #171e19;
      --yellow: #ffe17c;
      --gray-dark: #272727;
      --sage: #b7c6c2;
    }
    
    body {
      font-family: 'Satoshi', sans-serif;
      background-color: #ffffff;
      color: var(--charcoal);
      -webkit-font-smoothing: antialiased;
    }

    .font-anton {
      font-family: 'Anton', sans-serif;
      text-transform: uppercase;
      letter-spacing: normal;
      line-height: 0.9;
    }

    .bg-grid {
      background-size: 40px 40px;
      background-image: linear-gradient(to right, rgba(183, 198, 194, 0.2) 1px, transparent 1px), 
                        linear-gradient(to bottom, rgba(183, 198, 194, 0.2) 1px, transparent 1px);
    }

    .yellow-highlight {
      position: relative;
      display: inline-block;
      z-index: 1;
    }

    .yellow-highlight::before {
      content: '';
      position: absolute;
      bottom: 5px;
      left: -2%;
      width: 104%;
      height: 35%;
      background-color: var(--yellow);
      z-index: -1;
      transform: rotate(-1deg);
    }

    .parallax-shape {
      transition: transform 0.1s ease-out;
    }

    @keyframes slow-rotate {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }

    .animate-slow-rotate {
      animation: slow-rotate 15s linear infinite;
    }

    .transition-custom {
      transition: all 300ms cubic-bezier(0.4, 0, 0.2, 1);
    }

    .card-hover:hover .shape-hover {
      transform: rotate(45deg) scale(1.1);
      background-color: var(--yellow);
    }
  </style>
</head>
<body>
  <div class="min-h-screen flex flex-col relative w-full overflow-x-hidden">
    
    <!-- Navigation -->
    <nav class="fixed top-0 w-full h-20 bg-white/90 backdrop-blur-md z-50 border-b border-[#171e19]/10 flex items-center justify-between px-8 xl:px-12">
      <a href="#" id="nav-logo-link" class="font-anton text-3xl flex items-baseline">
        THE OVERLAP<span class="text-[#ffe17c] text-4xl">.</span>
      </a>
      <div class="hidden md:flex gap-10 items-center">
        <a href="#" id="nav-home-link" class="text-sm font-medium hover:text-[#b7c6c2] transition-colors uppercase tracking-widest">Home</a>
        <a href="#archive" id="nav-archive-link" class="text-sm font-medium hover:text-[#b7c6c2] transition-colors uppercase tracking-widest">Archive</a>
        <a href="#about" id="nav-about-link" class="text-sm font-medium hover:text-[#b7c6c2] transition-colors uppercase tracking-widest">About</a>
      </div>
      <div class="flex items-center gap-6">
        <a href="#signup" id="nav-subscribe-btn" class="bg-[#171e19] text-white px-8 py-3 rounded-full text-xs font-bold uppercase tracking-widest hover:bg-[#272727] transition-custom shadow-md hover:shadow-xl">
          Subscribe
        </a>
      </div>
    </nav>

    <!-- Main Content -->
    <main class="flex-1">
      
      <!-- Hero Section -->
      <section class="relative min-h-screen bg-grid flex items-center justify-center px-6 py-32 overflow-hidden">
        <!-- Floating Shapes -->
        <div class="absolute top-20 right-[15%] w-32 h-32 border-4 border-[#ffe17c] rounded-full opacity-20 parallax-shape" style="view-transition-name: hero-shape-1"></div>
        <div class="absolute bottom-20 left-[10%] w-48 h-48 bg-[#b7c6c2] rotate-12 opacity-10 animate-slow-rotate parallax-shape"></div>
        <div class="absolute top-1/2 left-[5%] w-20 h-20 bg-[#ffe17c] -rotate-45 opacity-20 parallax-shape"></div>
        
        <div class="max-w-5xl mx-auto flex flex-col items-center text-center z-10">
          <div class="inline-flex items-center gap-3 px-4 py-1.5 rounded-full border border-[#171e19]/10 bg-white/80 backdrop-blur-sm mb-12 shadow-sm">
            <span class="w-2.5 h-2.5 rounded-full bg-[#ffe17c] animate-pulse"></span>
            <span class="text-[10px] font-bold tracking-[0.3em] uppercase text-[#171e19]/80">Rebuilding in Public</span>
          </div>
          
          <h1 class="font-anton text-[clamp(3.5rem,10vw,8rem)] mb-10 tracking-tight leading-[0.85] text-[#171e19]">
            I BUILT TWO SEVEN-FIGURE BUSINESSES. <br>
            THEN I LOST <span class="yellow-highlight">EVERYTHING.</span>
          </h1>
          
          <div class="space-y-6 max-w-3xl">
            <p class="text-xl md:text-2xl text-[#171e19] font-bold leading-tight">
              I was an insecure kid who found success. Maybe I overcompensated. <br class="hidden md:block">
              Now I'm broke, frustrated, and figuring out who I actually am.
            </p>
            <p class="text-base md:text-lg text-[#171e19]/60 leading-relaxed">
              I had 180K subscribers. Made millions. Got hated. Got praised. Couldn't tell which was real. Lost it all. Now I sit at the same computer where money used to come to me. And nothing. Some days I hate myself. Some days I'm learning. Most days it's both. <span class="text-[#171e19] font-bold">But I still know things.</span> This is The Overlap: what I learned when I had it, what I'm learning now that I don't.
            </p>
          </div>
          
          <form class="w-full max-w-xl mt-14 flex flex-col sm:flex-row gap-4 relative z-20" onsubmit="event.preventDefault();">
            <input type="email" placeholder="Your best email..." required 
                   class="flex-1 px-8 py-5 rounded-2xl border-2 border-[#171e19]/10 bg-white/90 shadow-sm focus:outline-none focus:border-[#ffe17c] text-lg transition-custom">
            <button type="submit" 
                    class="bg-[#ffe17c] text-[#171e19] font-anton text-2xl px-12 py-5 rounded-2xl hover:bg-[#ffeb99] transition-custom shadow-xl hover:-translate-y-1 active:translate-y-0">
              SUBSCRIBE
            </button>
          </form>
          
          <p class="text-sm text-[#171e19]/40 mt-6 font-medium tracking-wide uppercase">
            No bullshit. No gurus. Just what's real.
          </p>
        </div>
      </section>

      <!-- Value Props -->
      <section class="py-32 bg-white border-y border-[#171e19]/10 relative">
        <div class="max-w-7xl mx-auto px-8">
          <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
            
            <!-- Value 1 -->
            <div class="bg-[#f8f9fa] p-10 rounded-3xl border border-[#171e19]/5 transition-custom hover:shadow-2xl hover:-translate-y-2 group">
              <div class="w-12 h-12 bg-[#171e19] text-white flex items-center justify-center rounded-xl mb-8 group-hover:bg-[#ffe17c] group-hover:text-[#171e19] transition-colors">
                <iconify-icon icon="ph:briefcase-bold" class="text-2xl"></iconify-icon>
              </div>
              <h3 class="font-anton text-3xl mb-4">REAL EXPERTISE</h3>
              <p class="text-[#171e19]/60 leading-relaxed">
                Direct response marketing, AI systems, and music business strategy at scale. I'm not theorizing; I built seven-figure audiences from scratch.
              </p>
            </div>

            <!-- Value 2 -->
            <div class="bg-[#f8f9fa] p-10 rounded-3xl border border-[#171e19]/5 transition-custom hover:shadow-2xl hover:-translate-y-2 group">
              <div class="w-12 h-12 bg-[#171e19] text-white flex items-center justify-center rounded-xl mb-8 group-hover:bg-[#ffe17c] group-hover:text-[#171e19] transition-colors">
                <iconify-icon icon="ph:heart-break-bold" class="text-2xl"></iconify-icon>
              </div>
              <h3 class="font-anton text-3xl mb-4">HONEST STRUGGLE</h3>
              <p class="text-[#171e19]/60 leading-relaxed">
                I'm not pretending. I'm rebuilding from a position of debt and frustration. You're getting the raw, unfiltered truth of what it takes to start over.
              </p>
            </div>

            <!-- Value 3 -->
            <div class="bg-[#f8f9fa] p-10 rounded-3xl border border-[#171e19]/5 transition-custom hover:shadow-2xl hover:-translate-y-2 group">
              <div class="w-12 h-12 bg-[#171e19] text-white flex items-center justify-center rounded-xl mb-8 group-hover:bg-[#ffe17c] group-hover:text-[#171e19] transition-colors">
                <iconify-icon icon="ph:lightning-bold" class="text-2xl"></iconify-icon>
              </div>
              <h3 class="font-anton text-3xl mb-4">ACTUAL TACTICS</h3>
              <p class="text-[#171e19]/60 leading-relaxed">
                AI frameworks that actually matter to musicians and marketers. No fluff, just technical exploits and creative strategies I'm using right now.
              </p>
            </div>

          </div>
        </div>
      </section>

      <!-- Featured Issue (Abstract Bento) -->
      <section class="py-24 px-8">
        <div class="max-w-6xl mx-auto">
          <div class="bg-[#171e19] text-white rounded-[3rem] p-12 lg:p-20 relative overflow-hidden flex flex-col lg:flex-row gap-16 card-hover shadow-2xl transition-custom">
            <!-- Abstract Background Shapes -->
            <div class="absolute top-0 right-0 w-full h-full pointer-events-none">
              <div class="absolute -right-20 -top-20 w-[400px] h-[400px] border-[40px] border-[#272727] rounded-full opacity-20"></div>
              <div class="absolute -right-10 bottom-20 w-32 h-32 bg-[#ffe17c] opacity-5 rotate-45 shape-hover transition-transform duration-700"></div>
            </div>

            <div class="flex-1 relative z-10">
              <span class="text-[#ffe17c] font-bold tracking-widest uppercase text-xs mb-6 block">Featured Issue</span>
              <h2 class="font-anton text-6xl md:text-7xl mb-8 leading-[0.9]">I WAS AN INSECURE KID <br> WHO FOUND SUCCESS.</h2>
              <p class="text-[#b7c6c2] text-xl font-medium mb-10 max-w-xl">
                And then I lost it. Here's exactly what I'm learning from the collapse, and why I'm rebuilding with a completely different mindset.
              </p>
              <a href="#" id="featured-read-link" class="inline-flex items-center gap-4 text-white hover:text-[#ffe17c] transition-colors group">
                <span class="font-anton text-2xl uppercase">Read the Full Story</span>
                <iconify-icon icon="ph:arrow-right-bold" class="text-2xl group-hover:translate-x-3 transition-transform"></iconify-icon>
              </a>
            </div>

            <div class="flex-1 flex items-center justify-center relative">
              <div class="w-full aspect-square max-w-[400px] relative">
                <!-- Abstract visual representing 'broken but structured' -->
                <div class="absolute inset-0 border-2 border-[#b7c6c2]/20 rotate-12 transition-transform duration-1000 group-hover:rotate-45"></div>
                <div class="absolute inset-4 border-2 border-[#b7c6c2]/40 -rotate-12 transition-transform duration-1000 group-hover:-rotate-90"></div>
                <div class="absolute inset-12 bg-[#272727] flex items-center justify-center">
                   <div class="w-24 h-24 bg-[#ffe17c] animate-pulse rounded-sm"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Issue Archive -->
      <section id="archive" class="py-32 px-8 max-w-7xl mx-auto">
        <div class="flex justify-between items-baseline mb-20">
          <h2 class="font-anton text-6xl lg:text-7xl">RECENT <br> <span class="text-[#b7c6c2]">ISSUES.</span></h2>
          <a href="#" id="view-all-issues" class="hidden md:block font-bold uppercase tracking-widest text-sm hover:text-[#b7c6c2] transition-colors">View All Archive</a>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 auto-rows-[340px]">
          
          <!-- Card 1 -->
          <div class="group bg-[#f8f9fa] p-8 rounded-3xl border border-[#171e19]/10 relative overflow-hidden transition-custom hover:shadow-2xl hover:-translate-y-2 flex flex-col">
             <div class="flex gap-2 mb-6">
                <span class="px-3 py-1 bg-[#171e19] text-white text-[10px] font-bold uppercase rounded-full">AI</span>
                <span class="px-3 py-1 bg-[#b7c6c2]/20 text-[#171e19] text-[10px] font-bold uppercase rounded-full">Marketing</span>
             </div>
             <h3 class="font-anton text-3xl mb-4 group-hover:text-[#b7c6c2] transition-colors">WHY I OVERCOMPENSATED <br> (AND WHAT IT COST ME)</h3>
             <p class="text-sm text-[#171e19]/60 line-clamp-3 mb-auto">
               An honest look at the ego trip that comes with seven figures, and the price you pay when you lose touch with why you started.
             </p>
             <div class="mt-8 flex justify-between items-center opacity-0 group-hover:opacity-100 transition-opacity">
                <span class="text-xs font-bold uppercase tracking-widest">Read More</span>
                <iconify-icon icon="ph:plus-bold" class="text-xl"></iconify-icon>
             </div>
             <div class="absolute -right-4 -bottom-4 w-24 h-24 bg-[#ffe17c]/20 rounded-full group-hover:scale-150 transition-transform duration-700"></div>
          </div>

          <!-- Card 2: Spans 2 cols -->
          <div class="group lg:col-span-2 bg-[#171e19] text-white p-8 rounded-3xl border border-white/5 relative overflow-hidden transition-custom hover:shadow-2xl hover:-translate-y-2 flex flex-col">
             <div class="flex gap-2 mb-6">
                <span class="px-3 py-1 bg-[#ffe17c] text-[#171e19] text-[10px] font-bold uppercase rounded-full">Exploit</span>
                <span class="px-3 py-1 bg-white/10 text-white text-[10px] font-bold uppercase rounded-full">Tech</span>
             </div>
             <div class="md:w-1/2 relative z-10">
                <h3 class="font-anton text-4xl mb-4 group-hover:text-[#ffe17c] transition-colors uppercase">THE REVERSE PROMPT <br> FRAMEWORK</h3>
                <p class="text-gray-400 mb-8">
                  Most musicians use AI backwards. This is the exact workflow I'm using to unlock authentic creativity at 10X speed without the "AI slop."
                </p>
             </div>
             <div class="absolute right-[-5%] bottom-[-10%] opacity-5 group-hover:opacity-10 transition-opacity duration-700">
                <iconify-icon icon="ph:circuitry-bold" class="text-[300px]"></iconify-icon>
             </div>
             <div class="mt-auto">
                <a href="#" class="inline-flex items-center gap-2 font-anton text-xl uppercase text-[#ffe17c]">Access the Framework <iconify-icon icon="ph:arrow-right"></iconify-icon></a>
             </div>
          </div>

          <!-- Card 3 -->
          <div class="group bg-[#f8f9fa] p-8 rounded-3xl border border-[#171e19]/10 relative overflow-hidden transition-custom hover:shadow-2xl hover:-translate-y-2 flex flex-col">
             <div class="flex gap-2 mb-6">
                <span class="px-3 py-1 bg-[#171e19] text-white text-[10px] font-bold uppercase rounded-full">Direct Response</span>
             </div>
             <h3 class="font-anton text-3xl mb-4 group-hover:text-[#b7c6c2] transition-colors">WHAT MONEY HIDES <br> FROM YOU</h3>
             <p class="text-sm text-[#171e19]/60 line-clamp-3 mb-auto">
               Revenue masks inefficiencies. I learned more in one month of being broke than I did in three years of sitting on seven figures.
             </p>
          </div>

          <!-- Card 4 -->
          <div class="group bg-[#272727] text-white p-8 rounded-3xl border border-white/5 relative overflow-hidden transition-custom hover:shadow-2xl hover:-translate-y-2 flex flex-col">
             <div class="flex gap-2 mb-6">
                <span class="px-3 py-1 bg-[#ffe17c] text-[#171e19] text-[10px] font-bold uppercase rounded-full">Growth</span>
             </div>
             <h3 class="font-anton text-3xl mb-4 text-[#ffe17c]">BUILDING AUDIENCES <br> FROM NOTHING</h3>
             <p class="text-gray-400 line-clamp-3 mb-auto">
               You don't need a budget to build a list. You need resonance. Here's the plan for 0 to 1,000 without spending a dime.
             </p>
          </div>

          <!-- Card 5 -->
          <div class="group bg-[#f8f9fa] p-8 rounded-3xl border border-[#171e19]/10 relative overflow-hidden transition-custom hover:shadow-2xl hover:-translate-y-2 flex flex-col">
             <div class="flex gap-2 mb-6">
                <span class="px-3 py-1 bg-[#171e19] text-white text-[10px] font-bold uppercase rounded-full">Music</span>
                <span class="px-3 py-1 bg-[#b7c6c2]/20 text-[#171e19] text-[10px] font-bold uppercase rounded-full">AI</span>
             </div>
             <h3 class="font-anton text-3xl mb-4">THE CLAUDE DAW <br> EXPERIMENT</h3>
             <p class="text-sm text-[#171e19]/60 line-clamp-3">
               I used Claude to analyze my production style and rebuild my templates. The results were... surprising.
             </p>
          </div>

        </div>
      </section>

      <!-- Split Section -->
      <section class="w-full flex flex-col lg:flex-row min-h-[700px]">
        <!-- Left: The Past -->
        <div class="flex-1 bg-[#171e19] text-white p-12 lg:p-24 flex flex-col justify-center relative overflow-hidden">
          <div class="absolute top-0 right-0 p-8 opacity-5">
            <iconify-icon icon="ph:mask-sad-bold" class="text-[250px]"></iconify-icon>
          </div>
          <span class="text-[#b7c6c2] text-xs font-bold tracking-widest uppercase mb-4">The Version I Hated</span>
          <h2 class="font-anton text-6xl md:text-7xl mb-12 text-white">WHEN I HAD IT ALL</h2>
          <ul class="space-y-10 max-w-lg">
            <li class="flex items-start gap-5">
              <div class="bg-red-500/10 p-2.5 rounded-lg mt-1 shrink-0">
                <iconify-icon icon="ph:x-circle-bold" class="text-red-400 text-2xl"></iconify-icon>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">Overcompensating</h3>
                <p class="text-[#b7c6c2]">Faking confidence to hide the fact that I was still that same insecure kid.</p>
              </div>
            </li>
            <li class="flex items-start gap-5">
              <div class="bg-red-500/10 p-2.5 rounded-lg mt-1 shrink-0">
                <iconify-icon icon="ph:x-circle-bold" class="text-red-400 text-2xl"></iconify-icon>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">Chasing Praise</h3>
                <p class="text-[#b7c6c2]">Performative success that invited hate and fed an arrogance I didn't actually feel.</p>
              </div>
            </li>
            <li class="flex items-start gap-5">
              <div class="bg-red-500/10 p-2.5 rounded-lg mt-1 shrink-0">
                <iconify-icon icon="ph:x-circle-bold" class="text-red-400 text-2xl"></iconify-icon>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">The Stagnation</h3>
                <p class="text-[#b7c6c2]">Money came so easily that I stopped learning. I stopped being nerdy. I stopped being me.</p>
              </div>
            </li>
          </ul>
        </div>

        <!-- Right: The Future -->
        <div class="flex-1 bg-[#272727] text-white border-l-4 border-[#ffe17c] p-12 lg:p-24 flex flex-col justify-center relative overflow-hidden">
          <div class="absolute bottom-0 right-0 p-8 opacity-5">
            <iconify-icon icon="ph:mountains-bold" class="text-[250px]"></iconify-icon>
          </div>
          <span class="text-[#ffe17c] text-xs font-bold tracking-widest uppercase mb-4">Starting from Zero</span>
          <h2 class="font-anton text-6xl md:text-7xl mb-12 text-[#ffe17c]">WHO I'M BECOMING</h2>
          <ul class="space-y-10 max-w-lg">
            <li class="flex items-start gap-5">
              <div class="bg-[#ffe17c]/10 p-2.5 rounded-lg mt-1 shrink-0">
                <iconify-icon icon="ph:check-circle-bold" class="text-[#ffe17c] text-2xl"></iconify-icon>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">Building with Integrity</h3>
                <p class="text-gray-300">Removing the ego and focusing on the craft. No more performing, just creating.</p>
              </div>
            </li>
            <li class="flex items-start gap-5">
              <div class="bg-[#ffe17c]/10 p-2.5 rounded-lg mt-1 shrink-0">
                <iconify-icon icon="ph:check-circle-bold" class="text-[#ffe17c] text-2xl"></iconify-icon>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">Learning in Public</h3>
                <p class="text-gray-300">Admitting what I don't know and sharing the experiments that actually work.</p>
              </div>
            </li>
            <li class="flex items-start gap-5">
              <div class="bg-[#ffe17c]/10 p-2.5 rounded-lg mt-1 shrink-0">
                <iconify-icon icon="ph:check-circle-bold" class="text-[#ffe17c] text-2xl"></iconify-icon>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">The Intersection</h3>
                <p class="text-gray-300">Where my years of scale meet the ground-zero grit of rebuilding with AI.</p>
              </div>
            </li>
          </ul>
        </div>
      </section>

      <!-- Final CTA -->
      <section class="relative py-32 bg-[#ffe17c] overflow-hidden flex items-center justify-center min-h-[80vh]">
        <!-- Decorative Background Text -->
        <div class="absolute inset-0 flex flex-col justify-center items-center pointer-events-none opacity-5 select-none">
          <h2 class="font-anton text-[18vw] leading-none whitespace-nowrap text-[#171e19]">THE OVERLAP THE OVERLAP</h2>
          <h2 class="font-anton text-[18vw] leading-none whitespace-nowrap text-[#171e19]">THE OVERLAP THE OVERLAP</h2>
        </div>

        <div class="relative z-10 max-w-4xl mx-auto px-6 text-center">
          <h2 class="font-anton text-7xl md:text-9xl text-[#171e19] mb-8 leading-[0.85]">
            I'M LEARNING.<br>JOIN ME.
          </h2>
          <p class="text-xl md:text-2xl text-[#171e19]/80 font-bold mb-14 max-w-2xl mx-auto">
            Weekly insights at the intersection of music, marketing, and AI. Real story. Real expertise. No bullshit.
          </p>
          
          <form class="flex flex-col sm:flex-row gap-4 max-w-2xl mx-auto mb-8" onsubmit="event.preventDefault();">
            <input type="email" placeholder="Join the overlap..." required 
                   class="flex-1 px-8 py-5 rounded-2xl border-2 border-[#171e19] bg-white text-lg font-bold focus:outline-none transition-custom">
            <button type="submit" 
                    class="bg-[#171e19] text-white font-anton text-2xl px-12 py-5 rounded-2xl hover:bg-[#272727] hover:scale-105 transition-custom shadow-2xl">
              GET ACCESS
            </button>
          </form>
          <div class="flex flex-col items-center gap-4">
             <p class="text-sm text-[#171e19]/60 font-medium">
                Join 500+ musicians and marketers figuring this out.
             </p>
             <p class="text-[10px] text-[#171e19]/40 font-bold uppercase tracking-widest">
                I wrote big checks to the gov, now I'm just here to grow.
             </p>
          </div>
        </div>
      </section>

    </main>

    <!-- Footer -->
    <footer class="bg-[#171e19] text-[#b7c6c2] py-20 px-8 border-t border-white/5">
      <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-16">
        <div class="space-y-6">
          <div class="font-anton text-3xl text-white">
            THE OVERLAP<span class="text-[#ffe17c]">.</span>
          </div>
          <p class="text-sm leading-relaxed max-w-xs opacity-70">
            Where years of seven-figure marketing scale meets the reality of rebuilding with AI from ground zero.
          </p>
        </div>
        <div class="flex flex-col gap-4">
          <span class="text-white font-anton text-lg tracking-widest mb-2">NAVIGATE</span>
          <a href="#" id="footer-archive-link" class="hover:text-[#ffe17c] transition-colors text-sm">The Archive</a>
          <a href="#" id="footer-about-link" class="hover:text-[#ffe17c] transition-colors text-sm">My Story</a>
          <a href="#" id="footer-contact-link" class="hover:text-[#ffe17c] transition-colors text-sm">Contact</a>
        </div>
        <div class="flex flex-col gap-4">
          <span class="text-white font-anton text-lg tracking-widest mb-2">CONNECT</span>
          <a href="#" id="footer-twitter-link" class="hover:text-[#ffe17c] transition-colors text-sm">Twitter / X</a>
          <a href="#" id="footer-youtube-link" class="hover:text-[#ffe17c] transition-colors text-sm">YouTube</a>
          <div class="mt-4 text-[10px] uppercase font-bold tracking-[0.2em] opacity-40">
             © 2024 The Overlap Newsletter.
          </div>
        </div>
      </div>
    </footer>
  </div>

  <script>
    // Subtle parallax for geometric shapes on scroll
    window.addEventListener('scroll', () => {
      const scrolled = window.pageYOffset;
      const shapes = document.querySelectorAll('.parallax-shape');
      
      shapes.forEach((shape, index) => {
        const speed = (index + 1) * 0.15;
        shape.style.transform = `translateY(${scrolled * speed}px) rotate(${scrolled * 0.05}deg)`;
      });
    });
  </script>
</body>
</html>
