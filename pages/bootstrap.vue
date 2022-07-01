<template>
  <div>
    <SectionBootstrap
      v-for="(item, i) in materi"
      :key="i"
      :bootstrap_materials="item"
    />
  </div>
</template>
<script>
export default {
  name: 'BootstrapPage',
  data() {
    return {
      materi: [
        {
          judul: '(7) Bootstrap',
          deskripsi: {
            summaryOne:
              'Bootstrap adalah framework HTML, CSS, dan JavaScript yang berfungsi untuk mendesain website responsive dengan cepat dan mudah. Bootstrap bersifat responsive berkat grid system yang digunakan. Sistem grid pada bootstrap menggunakan rangkaian containers, baris, dan kolom untuk menyesuaikan bentuk layout dan konten website.',
            summaryTwo:
              'Kegunaan Bootstrap -Menciptakan website Mobile Friendly —Berkat sistem grid, proses membuat website mobile friendly tak akan membutuhkan waktu lama. -Memudahkan resize gambar — Cukup dengan menambahkan class .img-responsive ke gambar, maka gambar tersebut akan otomatis di-resize sesuai ukuran layar pengguna. -Menambahkan elemen website tanpa ribet — Bootstrap menyediakan berbagai elemen yang bisa langsung Anda gunakan di website. Misalnya, navigasi, menu dropdown, thumbnail, dan sebagainya.',
            summaryThree:
              'Bootstrap juga memungkinkan Anda menggunakan plugin custom JQuery. Jadi, Anda bisa menambahkan berbagai elemen interaktif ke website dengan mudah. Misalnya, popup, transisi, image carousel, dan sebagainya.',
          },

          foto: '/assets/bootstrap.png',
        },
      ],
    }
  },
}
</script>
