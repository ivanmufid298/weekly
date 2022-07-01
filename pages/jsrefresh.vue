<template>
  <div>
    <SectionJS v-for="(item, i) in materi" :key="i" :js_materials="item" />
  </div>
</template>
<script>
export default {
  name: 'JSRefreshPage',
  data() {
    return {
      materi: [
        {
          judul: '(8) JS Refreshment',
          deskripsi: {
            summaryOne:
              'Javascript Bahasa pemrograman yang high-level, scripting, untyped, dan interpreted',
            summaryTwo:
              'Fungsi Javascript fungsi dari javascript adalah membuat web jadi lebih dinamis dan interaktif, tidak hanya soal urusan front end, tapi javascript juga dapat dipakai untuk urusan back end.',
          },

          foto: '/assets/jsrefresh.png',
        },
      ],
    }
  },
}
</script>
