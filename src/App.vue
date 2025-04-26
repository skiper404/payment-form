<script setup></script>

<template>
  <main class="container mx-auto h-screen max-w-[1200px] rounded-xl bg-[#111723] p-5 text-white">
    <section class="flex flex-col gap-2">
      <div class="text-lg">Your balance</div>
      <div class="flex items-center gap-2">
        <div
          class="flex h-10 w-10 items-center justify-center rounded-full bg-[#fec018] p-4 text-2xl font-bold text-[#e56037] italic"
        >
          V
        </div>
        <span class="t ext-2xl font-semibold">$1,878.67</span>
      </div>
      <button
        class="my-4 w-full cursor-pointer rounded-lg bg-[#2475fe] py-2 font-semibold transition duration-300 hover:bg-[#2495fe] active:bg-[#2495fe]"
      >
        + Buy credits
      </button>
    </section>
    <section class="flex flex-col gap-4">
      <div class="flex items-center justify-between">
        <span>Payment cards</span>
        <span class="cursor-pointer text-[#2475fe] hover:text-[#2495fe]">+ Add Card</span>
      </div>
      <a
        id="mastercard"
        href="#mastercard"
        class="tratsition flex items-center justify-between rounded-lg border border-transparent outline-0 duration-300 target:border-gray-500 hover:border-gray-500"
      >
        <div class="flex items-center">
          <div class="m-2 w-20 rounded-xl bg-gray-700 p-2">
            <img src="/master-card.png" alt="visa" />
          </div>
          <div class="flex flex-col px-2">
            <span class="text-lg font-semibold">John Smith</span>
            <span class="text-sm text-[#aaaaaa]">**** 7573</span>
          </div>
        </div>
        <div class="flex">
          <div class="rounded-xl bg-[#d4e8fa] px-2 py-1 text-xs font-semibold text-[#2475fe]">
            Primary
          </div>
          <div class="px-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-6"
            >
              <path stroke-linecap="round" stroke-linejoin="round" d="m8.25 4.5 7.5 7.5-7.5 7.5" />
            </svg>
          </div>
        </div>
      </a>

      <a
        id="visa"
        href="#visa"
        class="tratsition flex items-center justify-between rounded-lg border border-transparent outline-0 duration-300 target:border-gray-500 hover:border-gray-500"
      >
        <div class="flex items-center">
          <div class="m-2 w-20 rounded-xl bg-gray-200 p-2 py-3">
            <img src="/visa.png" alt="visa" />
          </div>
          <div class="flex flex-col px-2">
            <span class="text-lg font-semibold">John Smith</span>
            <span class="text-sm text-[#aaaaaa]">**** 7573</span>
          </div>
        </div>
        <div class="flex">
          <!-- <div class="rounded-xl bg-[#d4e8fa] px-2 py-1 text-xs text-[#2475fe]">Primary</div> -->
          <div class="px-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-6"
            >
              <path stroke-linecap="round" stroke-linejoin="round" d="m8.25 4.5 7.5 7.5-7.5 7.5" />
            </svg>
          </div>
        </div>
      </a>

      <div class="rounded-lg bg-[#253138] p-3 text-gray-400">
        We are compliant with the payment card industry security standart.
      </div>
    </section>
  </main>
</template>

<style lang="scss" scoped></style>
