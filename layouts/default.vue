<template>
  <div>
    <AppHeader />
    <main>
      <SideNav />
      <Nuxt class="pages" />
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

.pages {
  padding-left: 260px;
  /* z-index: 1;
  height: calc(100vh - 6.5em); */
}
</style>
