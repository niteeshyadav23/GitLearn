<template>
    <div class="nav flex space-between">
        <div class="logo">
            GitLearn
        </div>
        <div class="nav-option nav-links">
            <a class="btn">Home</a>
            <a class="btn">About</a>
            <a class="btn">Blog</a>
            <a class="btn">Contact</a>
            
        </div>
    </div>
</template>

<script setup></script>

<style>
/* Basic reset and font setting for the body */
body {
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f4f4f9;
}

/* Overall navigation container styling */
.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background-color: #fff;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* Logo styling */
.logo {
  font-size: 1.8rem;
  font-weight: 700;
  color: #333;
}

/* Container for the navigation links */
.nav-links {
  display: flex;
  gap: 1.5rem;
}

/* Styling for individual links (buttons) */
.nav-links a {
  text-decoration: none;
  color: #555;
  font-weight: 500;
  padding: 0.75rem 1.25rem;
  border-radius: 25px;
  transition: all 0.3s ease;
  background-color: #f0f0f5;
  border: 1px solid #e0e0e5;
}

/* Hover and active states for interactive feel */
.nav-links a:hover {
  color: #fff;
  background-color: #007bff;
  box-shadow: 0 4px 8px rgba(0, 123, 255, 0.3);
  transform: translateY(-2px);
}

.nav-links a:active {
  transform: translateY(0);
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
}

</style>