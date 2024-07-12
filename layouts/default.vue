<template>
  <div class="bg-[#151A38] text-white">
    <Header />
    <slot />
    <Footer />
    <div
      id="cursor-circle"
      class="fixed w-16 h-16 border border-yellow-300 rounded-full pointer-events-none transform -translate-x-1/2 -translate-y-1/2 hidden"
    ></div>
  </div>
</template>

<script setup>
import { onMounted } from 'vue';

onMounted(() => {
  const cursorCircle = document.getElementById("cursor-circle");

  document.addEventListener("mousemove", function (e) {
    cursorCircle.style.left = e.clientX + "px";
    cursorCircle.style.top = e.clientY + "px";
  });

  document.addEventListener("mouseenter", function () {
    cursorCircle.classList.remove("hidden");
  });

  document.addEventListener("mouseleave", function () {
    cursorCircle.classList.add("hidden");
  });
});
</script>
