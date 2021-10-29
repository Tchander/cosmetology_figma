<template>
  <div>
    <header-section />
    <main-section />
    <info-section />
    <news-section />
  </div>
</template>

<script>
import HeaderSection from "@/components/HeaderSection";
import MainSection from "@/components/MainSection";
import InfoSection from "@/components/InfoSection";
import NewsSection from "@/components/NewsSection";
export default {
  name: "Home",
  components: { NewsSection, InfoSection, MainSection, HeaderSection },
};
</script>
