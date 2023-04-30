<script setup>
import { Icon } from '#components'
const Check = h(Icon, { name: 'mdi:check-bold', size: 16 })
const Star = h(Icon, { name: 'mdi:star', size: 16 })
</script>

<template>
  <div>
    <div class="bg-gray-100 border-b-1 border border-b-gray-200 h-10 hidden sm:flex items-center px-4 justify-center">
      <div class="flex gap-8 text-xs items-center text-gray-400 container">
      
        <div class="flex gap-1 items-center">
          <Check class="text-emerald-600"/>
          <span>Founded in Poland. We respect your privacy.</span>
        </div>

        <div class="flex gap-1 items-center">
         <div class="flex items-center">
          <Star class="text-emerald-600"/>
          <Star class="text-emerald-600"/>
          <Star class="text-emerald-600"/>
          <Star class="text-emerald-600"/>
          <Star class="text-emerald-600"/>
         </div>
          <span>Used by 195,410 happy customers.</span>
        </div>
        <div class="flex gap-1 items-center">
          <Check class="text-emerald-600"/>
          <span>10,780,090+ professional games already played.</span>
        </div>
      </div>
    </div>
    <div class="flex justify-center">
      <div class="px-4 flex w-full justify-between items-center my-2 container">
        <div class="logo my-2">
          <img src="/assets/GambleNoko_e.svg" alt="logo"/>
        </div>
        <div class="menu text-xs flex gap-4 items-center">
          <ul class="hidden sm:flex gap-8">
            <li class="text-gray-400 hover:text-gray-800 cursor-pointer">Home</li>
            <li class="text-gray-400 hover:text-gray-800 cursor-pointer">About</li>
            <li class="text-gray-400 hover:text-gray-800 cursor-pointer">Contact</li>
            <li class="text-gray-400 hover:text-gray-800 cursor-pointer">Blog</li>
            <li class="text-gray-400 hover:text-gray-800 cursor-pointer">FAQ</li>
          </ul>
          <div class="flex gap-2">
            <button class="border-emerald-600/20 text-emerald-600 border px-4 py-2 rounded-md">Login</button>
            <button class="bg-emerald-600 text-white px-4 py-2 rounded-md">Get Started</button>
          </div>
        </div>
      </div>
    </div>

    <div class="flex justify-center">
    <div class="min-h-[400px] flex flex-col sm:flex-row gap-4 px-4 container justify-between items-top">
      
      <div class="left flex flex-col">
      <h1 class="text-4xl font-bold pt-10 font-[Poppins]">Professional Crypto Gambling <br>for true enthusiasts</h1>
      <h2 class="text-xl my-2">The #1 Professional Crypto Gambling Solution</h2>
      <span class="text-l">Try professional crypto gambling in minutes with our AI-integrated solution.<br> Load your balance, pick game & win.</span>
      <div class="flex items-center py-2">
          <Star class="text-emerald-600"/>
          <Star class="text-emerald-600"/>
          <Star class="text-emerald-600"/>
          <Star class="text-emerald-600"/>
          <Star class="text-emerald-600"/>
      </div>
      <i class="text-xs">Tens of thousands of people have played their professional gambling games with our platform.<br> Get your professinal crypto gambling experience today.</i>
      <button class="bg-emerald-600 text-white px-4 py-2 rounded-md mt-4">Get Started</button>
      </div>
      <div class="right flex items-center justify-center">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/EPwzirlb2rI?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      </div>

    </div>
  </div>


    <div class="bg-teal-200 py-12 px-4 flex justify-center w-full mt-4">
      <div class="flex gap-4 flex-col sm:flex-row justify-between container">
          <div>

            <div class="flex flex-col gap-2">
              <span class="font-bold font-xl font-[Poppins]">All games include</span>
              <div>
                <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>Tokenomics systems</span>
                </div>
                <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>Fair-Play mechanisms</span>
                </div>
                <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>High potentail revards</span>
                </div>
                <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>Small Gas Fee</span>
                </div>
              </div>
            </div>
          </div>

          <div>
            <span class="font-bold font-xl font-[Poppins]">Daily prices</span>
            
            <div class="flex gap-2 items-center">

                  <span class="text-3xl font-[Poppins] font-bold">37$ daily spin</span>
            </div>
            <div class="flex gap-2 items-center">
              <span class="text-3xl font-[Poppins] font-bold">3500$ in revards</span>
            </div>

     
          </div>

          <div>
            <span class="font-bold font-xl font-[Poppins]">Games</span>
            
            <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>Fortune Wheel</span>
            </div>
            <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>Black Jack</span>
            </div>
            <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>Casino</span>
            </div>
            <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>Roulette</span>
            </div>
            <div class="flex gap-2 items-center">
                  <Check class="text-emerald-600"/>
                  <span>Clash</span>
            </div>
          </div>
      </div>
    </div>

    <div class="bg-black">
      <div class="flex min-h-full min-h-[750px]">
        <div class="py-4 px-2 bg-slate-950 bg-opacity-30 hover:bg-opacity-90 w-full text-slate-100 min-h-full cursor-pointer hover:text-slate-50 hover:bg-slate-800 transition-all" style="background-image: url(https://images.pexels.com/photos/5477755/pexels-photo-5477755.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)">
          <span class="text-3xl font-[Poppins] font-bold">Casino</span>
        </div>
        <div class="py-4 px-2 bg-slate-950 text-slate-100 min-h-full cursor-pointer hover:text-slate-50 hover:bg-slate-800 transition-all" style="background-image: url(https://images.pexels.com/photos/4677402/pexels-photo-4677402.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)">
          <span class="text-3xl font-[Poppins] font-bold">Blackjack</span>
        </div>
        <div class="py-4 px-2 bg-slate-950 text-slate-100 min-h-full cursor-pointer hover:text-slate-50 hover:bg-slate-800 transition-all" style="background-image: url(https://images.pexels.com/photos/269630/pexels-photo-269630.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)">
          <span class="text-3xl font-[Poppins] font-bold">Cards</span>
        </div>
        <div class="py-4 px-2 bg-slate-950 text-slate-100 min-h-full cursor-pointer hover:text-slate-50 hover:bg-slate-800 transition-all" style="background-image: url(https://images.pexels.com/photos/6664193/pexels-photo-6664193.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)">
          <span class="text-3xl font-[Poppins] font-bold">Roulette</span>
        </div>
      </div>
    </div>
  </div>
</template>
