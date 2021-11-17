<template>
  <div>
    <header-section />
    <main-section />
    <info-section />
    <news-section />
    <actual-section />
    <contacts-section />
    <footer-section />
  </div>
</template>

<script>
import HeaderSection from "@/components/HeaderSection";
import MainSection from "@/components/MainSection";
import InfoSection from "@/components/InfoSection";
import NewsSection from "@/components/NewsSection";
import ActualSection from "@/components/ActualSection";
import ContactsSection from "@/components/ContactsSection";
import FooterSection from "@/components/FooterSection";
export default {
  name: "Home",
  components: {
    FooterSection,
    ContactsSection,
    ActualSection,
    NewsSection,
    InfoSection,
    MainSection,
    HeaderSection,
  },
};
</script>
