<template>
  <div>
    <h1>IDX</h1>
  </div>
</template>
<script>
export default {
  beforeMount() {
    console.log("idx page", ihfKestrel);
    // document.currentScript.replaceWith(ihfKestrel.render());
    ihfKestrel.render();
  },
};
</script>