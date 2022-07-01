<template>
  <div>
    <VersionControl v-for="(item, i) in materi" :key="i" :materials="item" />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      materi: [
        {
          judul: '(2) Version Control and Branch Management (Git)',
          deskripsi: {
            summaryOne:
              'Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project.',
            summaryTwo:
              'GitHub merupakan layanan cloud yang berguna untuk menyimpan dan mengelola sebuah project yang dinamakan repository (repo git). Cara kerja pada GitHub harus terkoneksi pada internet sehingga tidak perlu meng-install sebuah software ke dalam perangkat keras. Hal ini memberikan keringanan penyimpanan komputer yang kita gunakan karena file project tersimpan oleh cloud GitHub.',
          },

          foto: '/assets/git.png',
        },
      ],
    }
  },
}
</script>
