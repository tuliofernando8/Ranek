<template>
  <section>
    <h2>Endereço de envio</h2>
    <UsuarioForm>
      <button class="btn" @click.prevent="finalizarCompra">Finalizar Compra</button>
    </UsuarioForm>
  </section>
</template>

<script>
import UsuarioForm from "@/components/UsuarioForm.vue";
export default {
  name: "FinalizarCompra",
  components: {
    UsuarioForm
  },
  props: ["produto"]
}
</script>

<style>

</style>