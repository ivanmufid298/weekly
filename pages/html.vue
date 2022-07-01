<template>
  <div>
    <SectionHtml v-for="(item, i) in materi" :key="i" :html_materials="item" />
  </div>
</template>
<script>
export default {
  name: 'HTMLPage',
  data() {
    return {
      materi: [
        {
          judul: '(5) HTML',
          deskripsi: {
            summaryOne:
              'HTML Hypertext Markup Language atau HTML adalah bahasa markup standar yang digunakan untuk membuat halaman website dan aplikasi web.',
            summaryTwo:
              'Cara Kerja HTML File HTML diakhiri dengan ekstensi .html atau .htm. Ekstensi file ini bisa dilihat dengan mengunakan web browser apa pun (seperti Google Chrome, Safari, atau Mozila Firefox). Browser tersebut membaca file HTML dan merender kontennya sehingga user internet bisa melihat dan membacanya.',
            summaryThree:
              'Kelebihan dan kekurangan HTML Berikut kelebihan HTML: -Digunakan secara luas dan memiliki banyak sumber serta komunitas yang besar. -Dijalankan secara alami di setiap web browser. -Mudah dipelajari. -Open-source dan sepenuhnya gratis. -Rapi dan konsisten. -Menjadi standar resmi web, dikelola oleh (W3C). -Integrasi mudah dengan bahasa backend, seperti PHP dan Node.js.',
          },

          foto: '/assets/html.png',
        },
      ],
    }
  },
}
</script>
