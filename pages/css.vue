<template>
  <div>
    <SectionCSS v-for="(item, i) in materi" :key="i" :css_materials="item" />
  </div>
</template>
<script>
export default {
  name: 'CSSPage',
  data() {
    return {
      materi: [
        {
          judul: '(6) CSS',
          deskripsi: {
            summaryOne:
              'CSS adalah singkatan dari Cascading Style Sheets. Berisi rangkaian instruksi yang menentukan bagiamana suatu text akan ditampilkan pada halaman web. Perancangan desain text dapat dilakukan dengan mendefinisikan fonts (huruf) , colors (warna), margins (ukuran), latar belakang (background), ukuran font (font sizes) dan lain-lain. Cascading Style Sheets juga bisa berarti meletakkan styles yang berbeda pada layers (lapisan) yang berbeda. CSS terdiri dari style sheet yang memberitahukan browser bagaimana suatu dokumen akan disajikan. Fitur-fitur baru pada halaman web lama dapat ditambahkan dengan bantuan style sheet.',
            summaryTwo:
              'Cara menaruh CSS ada 3 teknik yaitu inline, internal, dan external',
            summaryThree:
              'Ada beberapa tipe CSS selector yaitu Element, class, dan id',
          },

          foto: '/assets/css.png',
        },
      ],
    }
  },
}
</script>
