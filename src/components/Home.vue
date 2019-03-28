<template>
  <div id="home">
    <h1>{{ msg }}</h1>
    <button>Googleアカウントでログイン</button>
  </div>
</template>

<script>
export default {
  name: "home",
  data() {
    return {
      msg: "Welcom to MyMarkdown"
    };
  }
};
</script>
