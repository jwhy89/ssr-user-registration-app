<template>
  <nav class="navbar">
    <h1>
      <img
        id="header-title-image"
        src="~/assets/icon.png"
        alt="Gray App Store Icon"
      />
      Add new User Profile
    </h1>
  </nav>
</template>

<style scoped>
#header-title-image {
  padding-right: 2%;
}

.navbar {
  position: stick;
  top: 0;
  z-index: 1;
  border-bottom: var(--header-border-bottom);
}

h1 {
  color: #5b6983;
  font-size: 2rem;
  padding-top: 2%;
  padding-bottom: 4%;
  padding-left: 2%;
}
</style>
