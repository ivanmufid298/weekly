<template>
  <div>
    <SectionFEFundamental
      v-for="(item, i) in materi"
      :key="i"
      :fefund_materials="item"
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
          judul: '(10) Front-end Fundamental',
          deskripsi: {
            summaryOne:
              'HTML singkatan dari Hypertext Markup Language, merupakan bahasa markup standar untuk membuat dan menyusun halaman dan aplikasi web, file html diakhiri dengan ekstensi .html atau .htm. Tag HTML memiliki dua tipe utaman yaitu block-level dan inline tags. CSS singkatan dari Cascading Style Sheets, CSS dipakai untuk mendesain halaman depan atau tampilan website, CSS menangani tampilan dan rasa dari halaman website, CSS terdiri dari 3 macam, yaitu Inline, External, dan Internal Javascript merupakan script yang membuat halaman web menjadi hidup yang memungkinkan adanya interaksi dengan pengguna, javascript bisa ditulis langsung ke dalam kode HTML dari sebuah web dan berjalan otomatis saat halaman dimuat. Jika diibaratkan dengan manusia, HTML merupakan kerangka, CSS merupakan kulit dan pakaian, Javascript merupakan otak.',
            summaryTwo:
              'Node.js merupakan runtime environment untuk javascript, dengan node.js dapat menjalankan kode javascript dimanapun, tidak hanya terbatas pada lingkungan browser. NPM singkatan dari Node Package Manager, Tool ini merupakan command line yang dapat menginstal dan menguninstal package, mengelola versi dan dependensi yang diperlukan untuk menjalankan proyek. Git merupakan salah satu sistemn pengontrol versi (Version Control System) pada proyek perangkat lunak. Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.',
            summaryThree:
              'NPM adalah singkatan dari Node Package Module yang merupakan tool command line yang dapat menginstall dan menguninstall package, mengelola versi dan dependensi yang di perlukan untuk menjalanlan proyek.',
          },

          foto: '/assets/fefunda.png',
        },
      ],
    }
  },
}
</script>
