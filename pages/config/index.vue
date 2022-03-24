<template>
  <div class="cont">
    <headers />
        <div class="page">
          <div class="content-block">
            <!-- <h1>Configurações</h1> -->
            <div class="cards">
              <div class="card-one c">
                <h1>Cadastrar Usuario</h1>
                <img src="/sucata.png">
                <NuxtLink class="btn-ir" to="/cadastro_usuario">Selecionar</NuxtLink>                
              </div>

              <div class="card-two c">
                <h1>Consultar Usuario</h1>
                <img src="/produto.png">
                <NuxtLink class="btn-ir" to="/consulta_usuario">Selecionar</NuxtLink>                
              </div>
            </div>
          </div>
        </div>
    <footers />
  </div>
</template>

<script>
  
</script>

<style lang="scss" scoped>
  @import '@/pages/transacoes/transacoes.scss'
</style>