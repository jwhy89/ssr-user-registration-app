<template>
  <div>
    <div class="sidenav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <NuxtLink to="/">Add login details</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/usergroup">Select the user group</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/avatar">Add an avatar</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/submit">Submit the form</NuxtLink>
        </li>
      </ul>
      <img
        src="~/assets/app-icon.png"
        alt="App Store Icon"
        width="350"
        height="350"
      />
    </div>
  </div>
</template>

<style scoped>
.sidenav {
  height: calc(100vh - 6.5em);
  background-image: url('~/assets/side-background.png');
  padding-left: 10px;
  position: fixed;
  left: 0;
  width: 260px;
  overflow-y: auto;
}
ul {
  list-style: none; /* Remove default bullets */
}
li.nav-item a::before {
  content: '\2022'; /* Add content: \2022 is the CSS Code/unicode for a bullet */
  color: gray; /* Change the color */
  font-weight: bold; /* If you want it to be bold */
  display: inline-block; /* Needed to add space between the bullet and the text */
  width: 1em; /* Also needed for space (tweak if needed) */
  margin-left: 1em; /* Also needed for space (tweak if needed) */
}
li a.nuxt-link-exact-active::before {
  content: '\2022'; /* Add content: \2022 is the CSS Code/unicode for a bullet */
  color: green !important; /* Change the color */
  font-weight: bold; /* If you want it to be bold */
  display: inline-block; /* Needed to add space between the bullet and the text */
  width: 1em; /* Also needed for space (tweak if needed) */
  margin-left: 1em; /* Also needed for space (tweak if needed) */
}
</style>
