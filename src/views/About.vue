<template>
  <section>
    <page-header :pageTitle="`Whatsapp Instant Chat`"/>

    <h3>Apasih ini?</h3>
    <p>Website ini adalah WebApp sederhana menggunakan VueJS sebagai teknologi dan untuk tujuan studi. Kode ini open-source dan dapat ditemukan di <a href="https://github.com/edytk/Whatsapp-Instant-Chat" target="_blank">Github</a>.</p>

    <p>Tujuan dari web ini adalah untuk dapat mengirim pesan ke nomor whatsapp tanpa harus menambahkannya sebagai kontak di buku telepon.</p>

    </section>
</template>

<script>
import PageHeader from '@/components/PageHeader.vue'

export default {
  name: 'About',
  components: {
    PageHeader
  }
}
</script>

<style lang="stylus" scoped>
p
  padding-bottom 1.875rem /* 30/16 */
  margin-bottom 1.875rem /* 30/16 */
  border-bottom 1px solid rgba(#333, .1)
a
  color #000
  text-decoration underline
  &:hover,
  &:focus
    opacity 0.65
    text-decoration none
</style>
