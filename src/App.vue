<template>
  <main>
    <px-header />
    <px-assets-table />
  </main>
</template>

<script>
import PxHeader from "@/components/PxHeader";
import PxAssetsTable from "@/components/PxAssetsTable";

export default {
  name: "App",
  components: { PxHeader, PxAssetsTable }
};
</script>
