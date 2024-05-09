<template>
  <aside class="sidebar">
    <div class="sidebar-content">
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
      </ul>
    </div>
  </aside>
</template>

<style scoped>
.sidebar {
  width: 200px; /* Adjust width as needed */
  height: 100%; /* Extend sidebar to full height of the viewport */
  background-color: #f0f0f0; /* Sidebar background color */
  position: fixed; /* Fix the sidebar position */
  top: 0; /* Position from the top of the viewport */
  left: 0; /* Position from the left edge */
  overflow-y: auto; /* Enable vertical scrolling if content overflows */
}

.sidebar-content {
  padding: 20px;
}
ul {
  list-style-type: none;
  padding: 0;
}

li {
  padding: 10px;
}
</style>
