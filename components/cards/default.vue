<template>
  <div class="border rounded shadow-xl p-3">
    <h1 class="m-1">
      <strong>{{ data.title }}</strong>
    </h1>
    <p class="text-neutral-500 m-1 text-sm">{{ data.text }}</p>
    <button
      class="border text-neutral-600 text-sm rounded m-1 px-2 py-1 hover:bg-gray-200">
      Learn More
    </button>
  </div>
</template>

<script>
export default {
  props: { data: Object },
};
</script>
