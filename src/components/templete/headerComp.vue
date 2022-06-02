<template>
  <header class="menu-superior">
    <div class="menu-esquerdo">
      <router-link to=".../">Home</router-link>
      <span> | </span>
      <router-link to=".../jogadores">Jogadores</router-link>
      <span> | </span>
      <router-link to=".../times">times</router-link>
    </div>
    <div class="menudireito">
      <span>Sair</span>
    </div>
  </header>
</template>
<style>
header span {
  padding: 0 40px;
}
header.menu-superior {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
<script></script>
