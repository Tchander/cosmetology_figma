<template>
  <div>
    <header-section />
    <main-section />
    <info-section />
  </div>
</template>

<script>
import HeaderSection from "@/components/HeaderSection";
import MainSection from "@/components/MainSection";
import InfoSection from "@/components/InfoSection";
export default {
  name: "Home",
  components: { InfoSection, MainSection, HeaderSection },
};
</script>
