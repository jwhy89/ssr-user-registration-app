<template>
  <div>
    <AppHeader />
    <main>
      <div>
        <SideNav />
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

/* main {
  display: block;
} */
</style>
