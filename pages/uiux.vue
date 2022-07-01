<template>
  <div>
    <IntroUiUx v-for="(item, i) in materi" :key="i" :ui_materials="item" />
  </div>
</template>

<script>
export default {
  name: 'UIUXPage',
  data() {
    return {
      materi: [
        {
          judul: '(3) Introduction UI dan UX',
          deskripsi: {
            summaryOne:
              'UI is visual that user uses to interact with your product artinya UI Designer lebih fokus pada visualisasi, coloring, dan hal-hal yang berkaitan dengan kreativitas dari interface yang akan digunakan oleh user.',
            summaryTwo:
              'UX is evrything that users feek everytime they re useing a product artinya UX Design memiliki ranah yang lebih luas dari UI. UX berfokus pada proses pembuatan produk hingga mampu mendapatkan pengalaman kemudahan dari user. Tanggung jawab seorang UX Designer adalah memastikan bahwa langkah demi langkah berjalan dengan logis dan jelas, serta memahami kebutuhan user.',
            summaryThree:
              'A simulation or sample version of a final product artinya proses terakhir dari produk situs web / aplikasi, Jadi sangat ideal untuk digunakan untuk menguji potensi masalah aplikasi sebelum pindah ke tahap pengembangan.',
          },

          foto: '/assets/uiux.png',
        },
      ],
    }
  },
}
</script>
