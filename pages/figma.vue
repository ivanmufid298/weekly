<template>
  <div>
    <FigmaDesign v-for="(item, i) in materi" :key="i" :figma_materials="item" />
  </div>
</template>
<script>
export default {
  name: 'FigmaPage',
  data() {
    return {
      materi: [
        {
          judul: '(4) Figma',
          deskripsi: {
            summaryOne:
              'Figma adalah aplikasi desain berbasis cloud dan alat prototyping untuk project digital. Figma dapat membantu para penggunanya berkolaborasi dalam suatu project atau pekerjaan dengan banyak pengguna secara real-time dan di mana saja.',
            summaryTwo:
              'Keuntungan menggunakan Figma adalah Gratis, Berjalan di Windows, Real-time team collaboration, dan Integrated high-quality prototyping',
            summaryThree:
              'Kelemahan nya adalah harus online saat ingin bekerja. tapi kita bisa menyimpan progressnya di local',
          },

          foto: '/assets/figma.png',
        },
      ],
    }
  },
}
</script>
