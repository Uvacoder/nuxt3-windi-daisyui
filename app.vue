<template>
  <div class="grid grid-cols-12">
    <LeftSidebar class="col-span-2" />
    <MainHolder class="bg-gray-300 border-r border-l border-black col-span-7" />
    <RightSidebar class="col-span-3" />
  </div>
</template>

<script>
export default {
  setup() {
    useMeta({
      htmlAttrs: {
        "data-theme": "light",
      },
    });
  },
};
</script>
