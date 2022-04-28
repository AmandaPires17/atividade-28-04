<script>
import BlocoUm from "@/components/BlocoUm.vue";

export default {
  data() {
    return {
      nomes2: ["Mariana", "Ariane"],
    };
  },
  components: { BlocoUm },
};
</script>
<template>
  <main id="content">
    <BlocoUm id="bloco1" :nomes="['Amanda', 'Antonia']" />

    <BlocoUm id="bloco2" titulo="Alunos" :nomes="nomes2"/>

    <BlocoUm id="bloco3" :nomes="['Bruna', 'Alessandra']" />

    <BlocoUm id="bloco4" :nomes="['Erol', 'Eloy']" />

    <BlocoUm id="bloco5" :nomes="['Rafael', 'Gabriel']" />

    <BlocoUm id="bloco6" :nomes="['Daniel', 'Jeferson']" />

    <BlocoUm id="bloco7" :nomes="['Roseli', 'Marino']" />

    <BlocoUm id="bloco8" :nomes="['Priscila', 'Alicealun']" />
  </main>
</template>
