<template>
  <div>
    <AppHeader />
    <main>
      <SideNav />
      <div class="pages">
        <Nuxt />
      </div>
    </main>
  </div>
</template>

<style>
@font-face {
  font-family: 'Proxima-Nova';
  src: url('~/assets/Proxima-Nova.ttf');
}

:root {
  --header-border-bottom: 1px solid#cfdee9;
}

* {
  box-sizing: border-box;
}

body {
  font-family: 'Proxima-Nova';
}

form {
  padding-left: 1em;
  padding-top: 1em;
}

.btn-position {
  position: absolute;
  bottom: 5%;
  right: 3%;
}

.divider {
  width: 5px;
  height: auto;
  display: inline-block;
}

.pages {
  padding-left: 260px;
  padding-right: 20px;
}
</style>
