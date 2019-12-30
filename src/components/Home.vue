<template>
  <div>Status of the server is {{ status }}</div>
</template>

<script>
export default {
  data: function() {
    return {
      status: "critical"
    };
  }
};
</script>
