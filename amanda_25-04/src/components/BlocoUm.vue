<script>
export default {
  props: {
    nomes: {
      type: Array,
    },
    titulo: {
      type: String,
      default: "Alunos",
    },
  },
  data() {
    return {};
  },
};
</script>
<template>

  <article class="block">
    {{ titulo }}
    <hr />
    <ul>
      <li v-for="nome of nomes" :key="nome">
      {{ nome }}
      </li>
    </ul>
  </article>

</template>
