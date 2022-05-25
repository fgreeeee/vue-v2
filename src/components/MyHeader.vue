<template>
  <div class="header">
    <li><a href="/" class="gl">Главная</a></li>
    <li><a href="/table_phys" class="tb">Таблица</a></li>
    <a href="/login" button type="button" class="log">Войти</a>
  </div>

</template>

<script>
export default {
  name: "MyHeader"
}
</script>

<style scoped>
.header{
  display: flex;
}



.gl{
  width: 300px;
  display: inline-block;
  color: black;
  font-weight: 700;
  text-decoration: none;
  user-select: none;
  padding: .5em 2em;
  border: 2px solid;
  border-radius: 1px;
}

.tb{
  width: 300px;
  display: inline-block;
  color: black;
  font-weight: 700;
  text-decoration: none;
  user-select: none;
  padding: .5em 2em;
  border: 2px solid;
  border-radius: 1px;
}

.log{
  position: absolute;
  left: 670px;
  top: 0px;
  width: 300px;
  display: inline-block;
  color: black;
  font-weight: 700;
  text-decoration: none;
  user-select: none;
  padding: .5em 2em;
  border: 2px solid;
  border-radius: 1px;
}
</style>