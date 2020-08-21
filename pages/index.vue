<template>
    <section class="chatbox">
        <input type="text" class="chatbox__input" placeholder="Escribe un nuevo mensaje...">
    </section>
</template>


<script>
export default {
    async asyncData({ $axios }) {
  const ip = await $axios.$get('https://api-test.comunal.co/session/test_comunal@comunal.co/Test_Comunal123/')
  return { ip }
},
methods: {

  async fetchSomething() {
  const ip = await $axios.$get('https://api-test.comunal.co/session/test_comunal@comunal.co/Test_Comunal123/');
      this.ip = ip
  }
},

}
</script>