<template>
  <header>
    <div class="container">
      <a
        href="https://ko.wikipedia.org/wiki/%EB%A1%9C%EB%A0%98_%EC%9E%85%EC%88%A8"
        target="_blank"
        >What is lipsum(Lorem ipsum?)</a
      >
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss" scoped>
header {
  width: 100%;
  height: 12rem;
  background-color: #2b2b2b;
  color: #e8e8e8;
  > div {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }
}
</style>
