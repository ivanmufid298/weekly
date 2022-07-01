<template>
  <div>
    <SectionVueFundamental
      v-for="(item, i) in materi"
      :key="i"
      :vuefund_materials="item"
    />
  </div>
</template>
<script>
export default {
  name: 'CleanCodePage',
  data() {
    return {
      materi: [
        {
          judul: '(11) Vue Fundamental',
          deskripsi: {
            summaryOne:
              'Vue Merupakan framework dari JavaScript untuk mengembangkan tampilan website yang lebih interaktif dan dinamis, Vue.js bertugas untuk menampilkan informasi kepada user sesuai dengan instruksi dari controller.',
            summaryTwo:
              'directive adalah atribut khusus vue yang diawali dengan v-, directive berfungsi untuk menjalankan satu perintah atau ekspresi javascript di dalam atribut.',
            summaryThree:
              'component adalah vue instance yang dapat digunakan kembali dengan nama yang kita definisikan. kita bisa menggunakan component ini sebagai kustom element di dalam instance root vue yang dibuat new vue.',
          },

          foto: '/assets/vue.png',
        },
      ],
    }
  },
}
</script>
