<template>
  <div>
    <SectionCleanCode
      v-for="(item, i) in materi"
      :key="i"
      :cleancode_materials="item"
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
          judul: '(9) Clean Code',
          deskripsi: {
            summaryOne:
              'Clean Code “Clean Code” sebagai salah satu aspek penting dalam software development tentu ada bukan tanpa sebab. Clean code pada pengembangan proyek khusunya perangkat lunak merupakan hal yang sebaiknya dilakukan oleh para developer.',
            summaryTwo:
              'Aturan umum -Mengikuti standar umum dalam bahasa pemrograman, contoh : Python (PEP 8) -KISS (Keep It Simple Stupid) , diusahakan untuk selalu seminimal mungkin dalam mengimplementasikan kode. -Cari akar permasalahan, jangan hanya bagian-bagian sekitar yang terkena dampak kode tersebut.',
          },

          foto: '/assets/cc.png',
        },
      ],
    }
  },
}
</script>
