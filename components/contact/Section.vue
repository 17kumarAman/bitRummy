<template>
  <div
    class="container mx-auto p-4 grid grid-cols-1 md:grid-cols-2 gap-8 mb-24"
  >
    <div class="grid grid-cols-1 gap-8 text-[#FFFFFF]">
      <div
        class="flex gap-4 md:gap-8 hover:bg-[#FFCE4F] rounded-lg bg-[#2F2B54] items-start p-5 md:p-10"
      >
        <div class="border rounded-full w-12 h-12 md:w-16 md:h-16 p-2 md:p-3">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            strokeWidth="1.5"
            stroke="currentColor"
            class="w-8 h-8 md:w-10 md:h-10"
          >
            <path
              strokeLinecap="round"
              strokeLinejoin="round"
              d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Z"
            />
          </svg>
        </div>
        <div>
          <h1 class="text-lg md:text-xl lg:text-2xl font-semibold">
            COMPANY NAME
          </h1>
          <p class="text-[#FFFDF6] text-sm md:text-base lg:text-lg">
            BITLECTRA INFOTECH PRIVATE <br />
            LIMITED
          </p>
        </div>
      </div>
      <!-- Repeat the above block for each section -->
      <div
        class="flex gap-4 md:gap-8 hover:bg-[#FFCE4F] rounded-lg bg-[#2F2B54] items-start p-5 md:p-10"
      >
        <div class="border rounded-full w-12 h-12 md:w-16 md:h-16 p-2 md:p-3">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            strokeWidth="1.5"
            stroke="currentColor"
            class="w-8 h-8 md:w-10 md:h-10"
          >
            <path
              strokeLinecap="round"
              strokeLinejoin="round"
              d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Z"
            />
          </svg>
        </div>
        <div>
          <h1 class="text-lg md:text-xl lg:text-2xl font-semibold">CONTACT</h1>
          <p class="text-[#FFFDF6] text-sm md:text-base lg:text-lg">
            BITLECTRA.888@GMAIL.COM & BITLECTRA@BITYRUMMY.IN <br />
            8000697562
          </p>
        </div>
      </div>
      <div
        class="flex gap-4 md:gap-8 hover:bg-[#FFCE4F] rounded-lg bg-[#2F2B54] items-start p-5 md:p-10"
      >
        <div class="border rounded-full w-12 h-12 md:w-16 md:h-16 p-2 md:p-3">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            strokeWidth="1.5"
            stroke="currentColor"
            class="w-8 h-8 md:w-10 md:h-10"
          >
            <path
              strokeLinecap="round"
              strokeLinejoin="round"
              d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Zm0 3h.008v.008h-.008v-.008Z"
            />
          </svg>
        </div>
        <div>
          <h1 class="text-lg md:text-xl lg:text-2xl font-semibold">ADDRESS</h1>
          <p class="text-[#FFFDF6] text-sm md:text-xl lg:text-lg">
            SHOP NO 48, SOUTH PART,<br />
            KALWAR KALWAD, JAIPUR, JAIPUR,<br />
            RAJASTHAN, 303706
          </p>
        </div>
      </div>
    </div>
    <div>
      <div class="p-5">
        <p class="text-lg md:text-start text-center">Get In Touch</p>
        <h1 class="text-center md:text-start text-4xl md:text-5xl lg:text-6xl">
          WE'RE <span class="text-[#FFCE4F]">HERE</span>  TO HELP YOU
        </h1>
      </div>
      <form action="" class="space-y-5">
        <input
          type="text"
          class="w-full h-10 text-black p-4 rounded-lg"
          placeholder="Name"
        />
        <input
          type="number"
          class="w-full h-10 text-black p-4 rounded-lg"
          placeholder="Mobile"
        />
        <input
          type="email"
          class="w-full h-10 text-black p-4 rounded-lg"
          placeholder="Email"
        />
        <textarea
          class="w-full h-20 text-black p-4 rounded-lg"
          placeholder="Message"
        ></textarea>
        <button
          class="w-full bg-yellow-600 h-12 md:h-16 rounded text-xl md:text-2xl"
        >
          Send
        </button>
      </form>
    </div>
  </div>
</template>
