<template>
  <div style="margin-left: 3%">
		<label>Estado</label>
		<input v-model="siglaCidade"  placeholder="Sigla do estado" />
		<button @click="getCidades">Buscar Cidade</button>
	</div>
</template>

<script>
export default {
    name: 'Cidade',
    data() {
        return {
            siglaCidade: '',
        }
    },

}
</script>

<style>

</style>