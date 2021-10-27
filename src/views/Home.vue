<template>
  <div>
    <header-section />
    <main-section />
  </div>
</template>

<script>
import HeaderSection from "@/components/HeaderSection";
import MainSection from "@/components/MainSection";
export default {
  name: "Home",
  components: { MainSection, HeaderSection },
};
</script>
