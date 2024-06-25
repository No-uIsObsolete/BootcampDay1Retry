<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br />
    <br />
      Hej Blockchain! <br />
      <br /> <button @click="podbij ">Podbij</button> <br />
      {{ licznik }}
  </main>
</template>

<script>
export default {
  data() {
    return {
      licznik: 0
    }
  },
  methods: {
    podbij() {
      this.licznik++
    }
  }
}
</script>
