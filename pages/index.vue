<template>
  <div class="font-sans">
    <Header />
    <div class="bg-red-700 p-60">
      <blockquote class="text-5xl text-white font-serif">
        “L’unica regola è non essere noiosi e vestire bene ovunque si vada. La
        vita è troppo breve per passare inosservati.”
      </blockquote>
    </div>
    <div class="p-20">
      <div class="flex flex-col">
        <div>LE NOSTRE CERTIFICAZIONI</div>
        <span class="text-gray-500 font-sans"
          >unici in Trentino Alto Adige.</span
        >
      </div>
      <div class="flex flex-row pt-20 pb-20 space-x-4">
        <div class="pr-10">
          <img src="@/assets/images/3mgraphics.png" alt="3M Preferred" />
          <div>
            <h3>3M Architectural Market</h3>
            <span class="text-sm text-gray-500"
              >certificazione x prodotti interior design</span
            >
          </div>
        </div>
        <div class="pr-10">
          <img src="@/assets/images/3minstaller.png" alt="3M Preferred" />
          <div>
            <h3>3M Windows Film</h3>
            <span class="text-sm text-gray-500"
              >certificazione per pellicole a controllo solare</span
            >
          </div>
        </div>
        <div>
          <img src="@/assets/images/3marchitectural.png" alt="3M Preferred" />
          <div>
            <h3>3M Endorsed</h3>
            <span class="text-sm text-gray-500"
              >certificazione legata al mondo del wrapping</span
            >
          </div>
        </div>
      </div>
      <Carwrapping />
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Carwrapping from '@/components/Carwrapping'
export default {
  components: {
    Header,
    Carwrapping,
  },
}
</script>

<style lang="postcss" scoped>
/* Style supports Taylwind. Learn more: https://tailwindcss.com/ */
</style>
