<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa Sukamulya</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Terlaksananya tata Kelola pemerintahan desa yang baik dan bersih guna mewujudkan kehidupan Masyarakat desa yang adil,Makmur dan Sejahtera.”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
         1.Melaksanakan Reformasi system kerja aparatur pemerintahan desa guna meningkatkan kwalitas pelayanan kepada Masyarakat.
        </li>
        <li>
         2.Menyelenggarakan pemerintahan desa yang bersih terbebas dari korupsi serta bentuk-bentuk penyelewengan lain nya.
        </li>
        <li>
       3.Menyelenggarakan pemerintahan desa secara terbuka dan bertanggung jawab sesuai dengan peraturan perundang-undangan.
        </li>
        <li>
         4.Meningkatkan perekonimian Masyarakat melalui pendampingan berupa penyuluhan khusus pada UKM, wiraswastan dan petani
        </li>
        <li>
        5.Meningkatkan mutu kesejahteraan Masyarakat untuk mencapai taraf kehidupan yang lebih baik dan layak,sehingga menjadi desa yang maju dan mandiri
        </li>
        <li>
         
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
