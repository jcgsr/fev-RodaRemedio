<template>
  <div class="w-screen flex-row box-border bg-blue-700">
    <h1 class="text-2xl p-2 w-screen font-bold bg text-center text-white">
      Formulário
    </h1>
    <div class="form w-screen">
      <form method="post" class="text-white text-center">
        <label for="remedio">Nome do Remédio:</label><br />
        <input
          name="remedio"
          class="bg-gray-200 pl-1 border m-1"
          placeholder="Nome do remédio"
          type="text"
        /><br />
        <label for="remedio">Onde Pegar:</label><br />
        <input
          name="local"
          class="bg-gray-200 pl-1 border m-1"
          placeholder="Local"
          type="text"
        />
      </form>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>


