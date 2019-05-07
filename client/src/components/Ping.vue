<template>
  <div class="container">
    <button type="button" class="btn btn-primary">{{ msg }}</button>
  </div>
</template>

<script>
export default {
  name: 'Ping',
  data() {
    return {
      msg: 'pong!',
    };
  },
};
</script>
