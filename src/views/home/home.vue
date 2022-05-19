<script setup lang="ts">
import './style.css'
import Header from './header.vue'

// import Block1 from './block-1.vue'

import Block2 from './block-2.vue'

</script>

<template>
  

  <div class="blue-bg"></div>

  <Header></Header>

  <div class="home-container">

  <div class="relative">
    <!-- <Block1></Block1>  -->
    
    <Block2></Block2>
    

    <div
      id="extwaiokist"
      style="display: none"
      v="efmeb"
      q="4f32c4ab"
      c="186.0"
      i="196"
      u="22.50"
      s="02142204"
      d="1"
      w="false"
      e=""
      m="BMe="
      vn="9axur"
    >
      <div
        id="extwaigglbit"
        style="display: none"
        v="efmeb"
        q="4f32c4ab"
        c="186.0"
        i="196"
        u="22.50"
        s="02142204"
        d="1"
        w="false"
        e=""
        m="BMe="
      ></div>
    </div>
  </div>

  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="py-4  overflow-hidden lg:py-8">
    <div class="relative max-w-xl mx-auto px-4 sm:px-6 lg:px-8 lg:max-w-7xl">
      <div class="relative mt-4 sm:mt-4 lg:mt-4">
        <div
          class="lg:grid lg:grid-flow-row-dense lg:grid-cols-2 lg:gap-8 lg:items-center py-24"
        >
          <div class="lg:col-start-2">
            <h2
              class="leading-6 text-green-600 font-semibold tracking-wide uppercase"
            >
              Launch Dates
            </h2>

            <h3
              class="mt-4 text-3xl leading-8 font-extrabold tracking-tight text-white sm:text-4xl"
            >
              <font _mstmutation="1"
                ><span class="text-green-600" _mstmutation="1">April 7th</span>
                Game launch
              </font>
            </h3>
            <p class="mt-4 text-lg text-white">
              <font _mstmutation="1"
                ><b class="text-white" _mstmutation="1">100,000</b> spots
                open for our Discord users
              </font>
            </p>
            <p class="text-lg text-white">
              Mint land <b class="text-white">NFTs</b> and start farming the
              SFL token
            </p>
            <h3
              class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-white sm:text-4xl"
            >
              <font _mstmutation="1"
                ><span class="text-green-600" _mstmutation="1">April 15th</span>
                Crafting launch
              </font>
            </h3>
            <p class="mt-4 text-lg text-white">
              <font _mstmutation="1"
                ><b class="text-white" _mstmutation="1">Craft</b> limited
                items &amp; exchange on
                <a
                  class="text-green-500 underline mt-1 inline"
                  href="https://opensea.io/collection/sunflower-land-collectibles"
                  target="_blank"
                  _mstmutation="1"
                  >Open Sea</a
                >
              </font>
            </p>
            <h3
              class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-white sm:text-4xl"
            >
              <font _mstmutation="1"
                ><span class="text-green-600" _mstmutation="1">May 9th</span>
                SFL launch
              </font>
            </h3>

            <p class="text-lg text-white mt-4">
              Withdraw <b class="text-white">SFL</b> and trade on QuickSwap
            </p>
          </div>
          <div class="mt-10 mx-4 relative lg:mt-0 lg:col-start-1">
            <!-- <iframe
              width="480"
              height="315"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen=""
            ></iframe> -->

            <img
              class="relative mx-auto rounded-lg"
              width="200"
              src="data:image/png;base64,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"
              alt=""
              style="image-rendering: pixelated"
            />
            
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="py-16  overflow-hidden lg:py-16">
    <div class="relative max-w-xl mx-auto px-4 sm:px-6 lg:px-8 lg:max-w-7xl">
      <!-- <svg
        class="hidden lg:block absolute left-full transform -translate-x-1/2 -translate-y-1/4"
        width="404"
        height="784"
        fill="none"
        viewBox="0 0 404 784"
        aria-hidden="true"
      >
        <defs>
          <pattern
            id="b1e6e422-73f8-40a6-b5d9-c8586e37e0e7"
            x="0"
            y="0"
            width="20"
            height="20"
            patternUnits="userSpaceOnUse"
          >
            <rect
              x="0"
              y="0"
              width="4"
              height="4"
              class="text-gray-200"
              fill="currentColor"
            ></rect>
          </pattern>
        </defs>
        <rect
          width="404"
          height="784"
          fill="url(#b1e6e422-73f8-40a6-b5d9-c8586e37e0e7)"
        ></rect>
      </svg> -->

      <div class="relative lg:grid lg:grid-cols-2 lg:gap-8 lg:items-center">
        <div class="relative">
          <h3
            class="text-2xl font-extrabold text-white tracking-tight sm:text-3xl"
          >
            Farm, Gather &amp; Earn SFL
          </h3>
          <p class="mt-3 text-lg text-white">
            From the gold you mine, to the sunflower seeds you plant, everything
            is an identifiable resource on Polygon.
          </p>

          <!-- <p class="mt-3 text-lg text-white">
              <a
                class="text-green-500 underline"
                href="https://polygonscan.com/token/0xD1f9c58e33933a993A3891F8acFe05a68E1afC05"
                >View token on Polygon Scan</a
              >
            </p> -->

          <dl class="mt-10 space-y-10">
            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-500 text-white"
                >
                  <!-- Heroicon name: outline/globe-alt -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                    ></path>
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-white">
                  Global Supply and Demand
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-white">
                The more resources that exist, the scarcer they become. Similar
                to
                <a
                  href="https://docs.sunflower-land.com/fundamentals/tokenomics#1.-natural-supply-and-demand"
                  class="underline"
                  >Bitcoin halving</a
                >, rewards become harder to earn over time.
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-500 text-white"
                >
                  <!-- Heroicon name: outline/scale -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M3 6l3 1m0 0l-3 9a5.002 5.002 0 006.001 0M6 7l3 9M6 7l6-2m6 2l3-1m-3 1l-3 9a5.002 5.002 0 006.001 0M18 7l3 9m-3-9l-6-2m0-2v2m0 16V5m0 16H9m3 0h3"
                    ></path>
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-white">
                  Secondary markets
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-white">
                Move your collectibles and resources freely between friends and
                on exchanges.
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-500 text-white"
                >
                  <!-- Heroicon name: outline/lightning-bolt -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"
                    ></path>
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-white">
                  100+ resources and NFTs
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-white">
                <font _mstmutation="1">
                  Everything you plant, chop, harvest, mine &amp; craft is a
                  token on Polygon. </font
                ><a
                  class="text-green-500 underline mt-1 block"
                  href="https://opensea.io/collection/sunflower-land-collectibles"
                  target="_blank"
                  >View on Open Sea</a
                >
              </dd>
            </div>
          </dl>
        </div>

        <div class="mt-10 -mx-4 relative lg:mt-0" aria-hidden="true">
          <svg
            class="absolute left-1/2 transform -translate-x-1/2 translate-y-16 lg:hidden"
            width="784"
            height="404"
            fill="none"
            viewBox="0 0 784 404"
          >
            <defs>
              <pattern
                id="ca9667ae-9f92-4be7-abcb-9e3d727f2941"
                x="0"
                y="0"
                width="20"
                height="20"
                patternUnits="userSpaceOnUse"
              >
                <rect
                  x="0"
                  y="0"
                  width="4"
                  height="4"
                  class="text-gray-200"
                  fill="currentColor"
                ></rect>
              </pattern>
            </defs>
            <rect
              width="784"
              height="404"
              fill="url(#ca9667ae-9f92-4be7-abcb-9e3d727f2941)"
            ></rect>
          </svg>
          <div class="relative mx-auto" style="width: 100%">
            <img
              class="relative"
              src="./assets/Soil.ccc4b087.png"
              alt=""
              style="
                -webkit-filter: drop-shadow(0px 4px 12px rgb(0 0 0 / 10%));
                width: 100%;
              "
            />
            <img
              class="mx-auto"
              src="./assets/watering.d848222a.gif"
              alt=""
              style="position: absolute; top: 4%; left: 3%; width: 71%"
            />
          </div>
        </div>
      </div>

      <!-- <svg
        class="hidden lg:block absolute right-full transform translate-x-1/2 translate-y-12"
        width="404"
        height="784"
        fill="none"
        viewBox="0 0 404 784"
        aria-hidden="true"
      >
        <defs>
          <pattern
            id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d"
            x="0"
            y="0"
            width="20"
            height="20"
            patternUnits="userSpaceOnUse"
          >
            <rect
              x="0"
              y="0"
              width="4"
              height="4"
              class="text-gray-200"
              fill="currentColor"
            ></rect>
          </pattern>
        </defs>
        <rect
          width="404"
          height="784"
          fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)"
        ></rect>
      </svg> -->

      <div class="relative mt-12 sm:mt-16 lg:mt-24">
        <div
          class="lg:grid lg:grid-flow-row-dense lg:grid-cols-2 lg:gap-8 lg:items-center"
        >
          <div class="lg:col-start-2">
            <h3
              class="text-2xl font-extrabold text-white tracking-tight sm:text-3xl"
            >
              Craft limited items and NFTs
            </h3>
            <p class="mt-3 text-lg text-white">
              Explore Sunflower Land to collect exotic resources in a race to
              craft and mint rare items.
            </p>

            <dl class="mt-10 space-y-10">
              <div class="relative">
                <dt>
                  <div
                    class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-500 text-white"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-6 w-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                      ></path>
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-white">
                    Burn what you earn
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-white">
                  Burn resources such as wood, stone, gold and iron to craft new
                  items.
                </dd>
              </div>

              <div class="relative">
                <dt>
                  <div
                    class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-500 text-white"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-6 w-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"
                      ></path>
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-white">
                    Functional NFTs and collectibles
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-white">
                  Earn 3x eggs with a chicken coop or grow wheat faster with a
                  scarecrow. No more boring JPEG NFTs!
                </dd>
              </div>

              <div class="relative">
                <dt>
                  <div
                    class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-green-500 text-white"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-6 w-6"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M21 15.546c-.523 0-1.046.151-1.5.454a2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.701 2.701 0 00-1.5-.454M9 6v2m3-2v2m3-2v2M9 3h.01M12 3h.01M15 3h.01M21 21v-7a2 2 0 00-2-2H5a2 2 0 00-2 2v7h18zm-3-9v-2a2 2 0 00-2-2H8a2 2 0 00-2 2v2h12z"
                      ></path>
                    </svg>
                  </div>
                  <p class="ml-16 text-lg leading-6 font-medium text-white">
                    Community events
                  </p>
                </dt>
                <dd class="mt-2 ml-16 text-base text-white">
                  Make sure you have enough eggs, beetroots and diamonds stored.
                  Rare items are released frequently. You want to be prepared
                  when the time comes!
                </dd>
              </div>
            </dl>
          </div>

          <div class="mt-10 -mx-4 relative lg:mt-0 lg:col-start-1">
            <svg
              class="absolute left-1/2 transform -translate-x-1/2 translate-y-16 lg:hidden"
              width="784"
              height="404"
              fill="none"
              viewBox="0 0 784 404"
              aria-hidden="true"
            >
              <defs>
                <pattern
                  id="e80155a9-dfde-425a-b5ea-1f6fadd20131"
                  x="0"
                  y="0"
                  width="20"
                  height="20"
                  patternUnits="userSpaceOnUse"
                >
                  <rect
                    x="0"
                    y="0"
                    width="4"
                    height="4"
                    class="text-gray-200"
                    fill="currentColor"
                  ></rect>
                </pattern>
              </defs>
              <rect
                width="784"
                height="404"
                fill="url(#e80155a9-dfde-425a-b5ea-1f6fadd20131)"
              ></rect>
            </svg>
            <img
              class="relative mx-auto rounded-lg"
              width="200"
              src="data:image/png;base64,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"
              alt=""
              style="image-rendering: pixelated"
            />
            <div class="mt-5 sm:mt-8 flex justify-center z-50 relative">
              <div class="rounded-md shadow mr-2">
                <a
                  href="https://opensea.io/collection/sunflower-land-collectibles"
                  class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-green-600 hover:bg-green-700 md:py-4 md:text-lg md:px-10"
                >
                  Open Sea
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- This example requires Tailwind CSS v2.0+ -->
  <div
    class="relative  pt-16 pb-20 px-4 sm:px-6 lg:pt-24 lg:pb-28 lg:px-8"
  >
    <div class="absolute inset-0">
      <div class="h-1/3 sm:h-2/3"></div>
    </div>
    <div class="relative max-w-7xl mx-auto">
      <div class="text-center">
        <h2
          class="text-3xl tracking-tight font-extrabold text-white sm:text-4xl"
        >
          The Sunflower Vision
        </h2>
        <p class="mt-3 max-w-2xl mx-auto text-xl text-white sm:mt-4">
          We are on a journey to become the #1 Crypto game that is built ground
          up by the community.
        </p>

        <a
          class="text-green-500 underline text-xl mt-1"
          href="https://docs.sunflower-land.com/fundamentals/roadmap"
          target="_blank"
          >View our roadmap</a
        >
      </div>
      <div
        class="mt-12 max-w-lg mx-auto grid gap-5 lg:grid-cols-3 lg:max-w-none"
      >
        <div class="flex flex-col rounded-lg shadow-lg overflow-hidden">
          <div class="flex-shrink-0">
            <img
              class="h-48 w-full object-cover"
              style="image-rendering: pixelated"
              src="./assets/crops.6da9c07d.png"
              alt=""
            />
          </div>
          <div class="flex-1 bg-white p-6 flex flex-col justify-between">
            <div class="flex-1">
              <p class="text-sm font-medium text-green-600">
                <a
                  href="https://docs.sunflower-land.com/fundamentals/roadmap"
                  class="hover:underline"
                >
                  Stage 1
                </a>
              </p>
              <a
                href="https://docs.sunflower-land.com/fundamentals/roadmap"
                class="block mt-2"
              >
                <p class="text-xl font-semibold text-gray-900">Beta farming</p>
                <dt class="mt-2">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    class="absolute h-6 w-6 text-green-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M5 13l4 4L19 7"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">
                    Farming &amp; Earn SFL
                  </p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    class="absolute h-6 w-6 text-green-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M5 13l4 4L19 7"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">
                    Crafting/Minting items
                  </p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    class="absolute h-6 w-6 text-green-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M5 13l4 4L19 7"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">Wood Chopping</p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    class="absolute h-6 w-6 text-green-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M5 13l4 4L19 7"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">Mining</p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    class="absolute h-6 w-6 text-green-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M5 13l4 4L19 7"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">Skill System</p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">Animals</p>
                </dt>
              </a>
            </div>
          </div>
        </div>

        <div class="flex flex-col rounded-lg shadow-lg overflow-hidden">
          <div class="flex-shrink-0">
            <img
              style="image-rendering: pixelated"
              class="h-48 w-full object-cover"
              src="./assets/expansion.e3dc339c.jpg"
              alt=""
            />
          </div>
          <div class="flex-1 bg-white p-6 flex flex-col justify-between">
            <div class="flex-1">
              <p class="text-sm font-medium text-green-600">
                <a
                  href="https://docs.sunflower-land.com/fundamentals/roadmap"
                  class="hover:underline"
                  >Stage 2</a
                >
              </p>
              <a
                href="https://docs.sunflower-land.com/fundamentals/roadmap"
                class="block mt-2"
              >
                <p class="text-xl font-semibold text-gray-900">
                  NFT Land expansion &amp; resource scarcity
                </p>
                <dt class="mt-2">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">Land expansion</p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">
                    Liquidity pool resource pricing
                  </p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">
                    Farm Character NFTs
                  </p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">
                    Fishing, Bees + new resources + NFTs
                  </p>
                </dt>
              </a>
            </div>
          </div>
        </div>

        <div class="flex flex-col rounded-lg shadow-lg overflow-hidden">
          <div class="flex-shrink-0">
            <img
              class="h-48 w-full object-cover"
              src="./assets/black_market.3bde9316.jpg"
              alt=""
              style="image-rendering: pixelated"
            />
          </div>
          <div class="flex-1 bg-white p-6 flex flex-col justify-between">
            <div class="flex-1">
              <p class="text-sm font-medium text-green-600">
                <a
                  href="https://docs.sunflower-land.com/fundamentals/roadmap"
                  class="hover:underline"
                  >Stage 3
                </a>
              </p>
              <a
                href="https://docs.sunflower-land.com/fundamentals/roadmap"
                class="block mt-2"
              >
                <p class="text-xl font-semibold text-gray-900">
                  Decentralised community protocols
                </p>
                <dt class="mt-2">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">
                    Goblin Black Market DEX
                  </p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">Community NFTs</p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">Sunflower DAO</p>
                </dt>
                <dt class="mt-1">
                  <!-- Heroicon name: outline/check -->
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="absolute h-6 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                    ></path>
                  </svg>
                  <p class="ml-9 text-base text-gray-500">NFT Trading House</p>
                </dt>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="">
    <div class="mx-auto py-12 px-4 max-w-7xl sm:px-6 lg:px-8 lg:py-24">
      <div class="grid grid-cols-1 gap-12 lg:grid-cols-3 lg:gap-8">
        <div class="space-y-5 sm:space-y-4">
          <h2 class="text-3xl font-extrabold tracking-tight sm:text-4xl">
            Thought Farm
          </h2>
          <p class="text-xl text-white">
            Sunflower Land was built by a team of passionate people who love
            building community driven projects
          </p>
          <p class="text-xl text-white">
            Built by over 40+ open source developers and 50+ designers across
            the globe.
          </p>
          <p class="text-xl text-white">
            <font _mstmutation="1">
              Want to help out? Come join us on
              <a
                class="text-green-500 underline"
                href="https://github.com/sunflower-farmers/sunflower-farmers"
                _mstmutation="1"
                >Github</a
              >
            </font>
          </p>
        </div>
        <div class="lg:col-span-2">
          <ul
            role="list"
            class="space-y-12 sm:grid sm:grid-cols-2 sm:gap-12 sm:space-y-0 lg:gap-x-8"
          >
            <li>
              <div class="flex items-center space-x-4 lg:space-x-6">
                <img
                  class="w-16 h-16 rounded-full lg:w-20 lg:h-20 object-cover"
                  src=""
                  alt=""
                />
                <div class="font-medium text-lg leading-6 space-y-1">
                  <h3>Adam Hannigan</h3>
                  <p class="text-green-600">
                    Founder, Designer &amp; Developer
                  </p>
                  <ul role="list" class="flex space-x-5">
                    <li>
                      <a
                        href="https://twitter.com/bumpkinbuilder"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">Twitter</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84"
                          ></path>
                        </svg>
                      </a>
                    </li>
                    <li>
                      <a
                        href="https://www.linkedin.com/in/%F0%9F%8C%BB-adam-hannigan-102489109/"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">LinkedIn</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </li>
            <li>
              <div class="flex items-center space-x-4 lg:space-x-6">
                <img
                  class="w-16 h-16 rounded-full lg:w-20 lg:h-20"
                  src="data:image/jpeg;base64,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"
                  alt=""
                />
                <div class="font-medium text-lg leading-6 space-y-1">
                  <h3>Spencer Dezart-Smith</h3>
                  <p class="text-green-600">Engineer (UX/Mobile Specialist)</p>
                  <ul role="list" class="flex space-x-5">
                    <li>
                      <a
                        href="https://twitter.com/thisboyspencer"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">Twitter</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84"
                          ></path>
                        </svg>
                      </a>
                    </li>
                    <li>
                      <a
                        href="https://www.linkedin.com/in/spencerdezartsmith/"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">LinkedIn</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </li>
            <li>
              <div class="flex items-center space-x-4 lg:space-x-6">
                <img
                  class="w-16 h-16 rounded-full lg:w-20 lg:h-20"
                  alt=""
                />
                <div class="font-medium text-lg leading-6 space-y-1">
                  <h3>Romy Furtado</h3>
                  <p class="text-green-600">Engineer &amp; Musician</p>
                  <ul role="list" class="flex space-x-5">
                    <li>
                      <a
                        href="https://twitter.com/rofrtd"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">Twitter</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84"
                          ></path>
                        </svg>
                      </a>
                    </li>
                    <li>
                      <a
                        href="https://www.linkedin.com/in/rofrtd/"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">LinkedIn</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </li>
            <li>
              <div class="flex items-center space-x-4 lg:space-x-6">
                <img
                  class="w-16 h-16 rounded-full lg:w-20 lg:h-20 object-cover"
                  alt=""
                />
                <div class="font-medium text-lg leading-6 space-y-1">
                  <h3>Steve Woody</h3>
                  <p class="text-green-600">
                    Partner, PR &amp; Community Management
                  </p>
                  <ul role="list" class="flex space-x-5">
                    <li>
                      <a
                        href="https://twitter.com/STEVEW00DY"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">Twitter</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84"
                          ></path>
                        </svg>
                      </a>
                    </li>
                    <li>
                      <a
                        href="https://www.linkedin.com/in/stevew00dy/"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">LinkedIn</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </li>
            <li>
              <div class="flex items-center space-x-4 lg:space-x-6">
                <img
                  class="w-16 h-16 rounded-full lg:w-20 lg:h-20 object-cover"
                  alt=""
                />
                <div class="font-medium text-lg leading-6 space-y-1">
                  <h3>Brandon Collins</h3>
                  <p class="text-green-600">
                    Advisor, Community Relations &amp; Support
                  </p>
                  <ul role="list" class="flex space-x-5">
                    <li>
                      <a
                        href="https://twitter.com/SFL_Roulette"
                        class="text-white hover:text-white"
                      >
                        <span class="sr-only">Twitter</span>
                        <svg
                          class="w-5 h-5"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          aria-hidden="true"
                        >
                          <path
                            d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84"
                          ></path>
                        </svg>
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </li>
          </ul>
          <!-- <iframe
            width="400"
            height="315"
            src="https://www.youtube.com/embed/b3ArEUUK52A"
            class="mt-12"
          >
          </iframe> -->
        </div>
      </div>
    </div>
  </div>

  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="">
    <div class="max-w-7xl mx-auto py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-extrabold text-white">
        Frequently asked questions
      </h2>
      <div class="mt-6 border-t border-green-300 border-opacity-25 pt-10">
        <dl
          class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-12"
        >
          <div>
            <dt class="text-lg leading-6 font-medium text-white">
              How do I play the game?
            </dt>
            <dd class="mt-2 text-base text-green-200">
              <font _mstmutation="1">
                You will need to set up your MetaMask with the Polygon
                blockchain. You can find more details
                <a
                  href="https://docs.sunflower-land.com/guides/getting-setup"
                  class="underline"
                  _mstmutation="1"
                  >here</a
                >
              </font>
            </dd>
          </div>

          <div>
            <dt class="text-lg leading-6 font-medium text-white">
              When Lambo?
            </dt>
            <dd class="mt-2 text-base text-green-200">
              Our focus is first building out tractors in Sunflower Land.
            </dd>
          </div>

          <div>
            <dt class="text-lg leading-6 font-medium text-white">
              Where can I swap the Sunflower Land Token?
            </dt>
            <dd class="mt-2 text-base text-green-200">Coming soon...</dd>
          </div>

          <div>
            <dt class="text-lg leading-6 font-medium text-white">
              How do I send tokens to my land?
            </dt>
            <dd class="mt-2 text-base text-green-200">
              <font _mstmutation="1">
                Each land NFT has a unique address on the blockchain you can
                send resources to. Find out more
                <a
                  href="https://docs.sunflower-land.com/guides/sending-sfl"
                  class="underline"
                  _mstmutation="1"
                  >here</a
                >
              </font>
            </dd>
          </div>

          <!-- More questions... -->
        </dl>
      </div>
    </div>
  </div>

  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="">
    <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 md:py-16 lg:px-8 lg:py-20">
      <h2
        class="text-3xl font-extrabold tracking-tight text-white sm:text-4xl"
      >
        <span class="block">Looking to learn more?</span>
        <span class="block text-green-600"
          >Read our litepaper &amp; tokenomics</span
        >
      </h2>
      <div class="mt-8 flex">
        <div class="inline-flex">
          <a
            href="https://docs.sunflower-land.com/fundamentals/tokenomics"
            class="inline-flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-green-700 bg-green-100 hover:bg-green-200"
          >
            Read more
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- This example requires Tailwind CSS v2.0+ -->
  <div
    class="max-w-7xl mx-auto py-12 px-4 sm:px-6 md:flex md:items-center md:justify-between lg:px-8"
  >
    <div class="rounded-md bg-green-50 p-4 w-full">
      <div class="flex">
        <div class="flex-shrink-0">
          <!-- Heroicon name: solid/information-circle -->
          <svg
            class="h-5 w-5 text-green-400"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20"
            fill="currentColor"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </div>
        <div class="ml-3 flex-1 md:flex md:justify-between">
          <p class="text-sm text-green-700">
            The information provided on this website does not constitute
            investment advice, financial advice, trading advice, or any other
            sort of advice and you should not treat any of the website’s content
            as such. Thought Farm Pty Ltd does not recommend that any
            cryptocurrency should be bought, sold, or held by you. The game uses
            a utility token that is not intended for purchase. The game can be
            played entirely without the need to purchase any token. Always do
            your own research
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- This example requires Tailwind CSS v2.0+ -->
  <footer class="">
    <div
      class="max-w-7xl mx-auto pt-12 px-4 sm:px-6 md:flex md:items-center md:justify-between lg:px-8"
    >
      <div class="flex justify-center space-x-6 md:order-2">
        <a
          href="https://twitter.com/0xSunflowerLand"
          class="text-white hover:text-white"
        >
          <span class="sr-only">Twitter</span>
          <svg
            class="h-6 w-6"
            fill="currentColor"
            viewBox="0 0 24 24"
            aria-hidden="true"
          >
            <path
              d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
            ></path>
          </svg>
        </a>

        <a
          href="https://github.com/sunflower-land/sunflower-land"
          class="text-white hover:text-white"
        >
          <span class="sr-only">GitHub</span>
          <svg
            class="h-6 w-6"
            fill="currentColor"
            viewBox="0 0 24 24"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </a>

        <a
          href="https://discord.gg/sunflowerland"
          class="text-white hover:text-white"
        >
          <span>Discord</span>
        </a>
      </div>
      <div class="mt-8 md:mt-0 md:order-1">
        <p class="text-center text-base text-white">
          © 2022 Sunflower Land. All rights reserved.
        </p>
        <!-- <p class="text-left text-base text-white">Thought Farm Pty Ltd</p>
        <p class="text-left text-base text-white">
          <font _mstmutation="1">info@sunflower-land.com</font>
        </p> -->
      </div>
    </div>
    <!-- <div class="w-full flex justify-center mb-4">
      <a
        href="https://docs.sunflower-land.com/support/terms-of-service"
        class="text-center underline text-base text-white"
      >
        Terms of service
      </a>
    </div> -->
  </footer>
</div>
</template>

<style scoped  >
/* @import './style.css'; */
</style>
