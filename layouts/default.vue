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

.pages {
  padding-left: 260px;
  padding-right: 20px;
}
</style>
