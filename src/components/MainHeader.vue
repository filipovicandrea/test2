<template>
  <header class="header">
    <div class="header-content">
      <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  width: 100%; /* Extend header to full width */
  background-color: #333; /* Header background color */
  color: #fff; /* Text color */
  position: fixed; /* Fix the header position */
  top: 0; /* Position from the top of the viewport */
  left: 200px; /* Position from the left edge, matching sidebar width */
  right: 0; /* Position from the right edge */
}

.header-content {
  display: flex; /* Use flexbox for layout */
  justify-content: space-between; /* Space items evenly */
  align-items: center; /* Align items vertically */
  padding: 10px 20px; /* Add padding as needed */
}

nav {
  display: flex; /* Use flexbox for navigation links */
}

nav a {
  color: #fff; /* Link text color */
  margin-right: 10px; /* Add margin between links */
  text-decoration: none; /* Remove underline from links */
}
</style>