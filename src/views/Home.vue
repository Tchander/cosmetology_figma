<template>
  <div>
    <header-section />
    <main-section />
    <info-section />
    <news-section />
    <actual-section />
  </div>
</template>

<script>
import HeaderSection from "@/components/HeaderSection";
import MainSection from "@/components/MainSection";
import InfoSection from "@/components/InfoSection";
import NewsSection from "@/components/NewsSection";
import ActualSection from "@/components/ActualSection";
export default {
  name: "Home",
  components: {
    ActualSection,
    NewsSection,
    InfoSection,
    MainSection,
    HeaderSection,
  },
};
</script>
