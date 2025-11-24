<template>
  <div class="">
    <h1>Documents {Coming soon}</h1>
        Curriculum Vitae<br />
        Ielts<br />
        Master<br />
        Bachelor<br />
        <button @click="openPdf">Presentation AI.care 2025</button>
    </div>
</template>

<script setup>
function openPdf() {
  const url = `${import.meta.env.BASE_URL}MonicaNoselli_MoreThanAccuracyHowAtificialIntelligenceOutputsArePresentedToClinicinasMatters.pdf`;
  window.open(url, '_blank');
}
</script>