<script setup></script>

<template>
  <div>
    <header>
   
    </header>
  <div>
    <slot />
  </div>

  <nav>
        <ul>
          <li>
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/products">Products</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">About</nuxt-link>
          </li>
        </ul>
      </nav>
  </div>
</template>

<style>
  header {
    background-color: #ae1717;
    color: white;
    padding: 1rem;
  }
  nav ul {
    display: flex;
    justify-content: space-between;
    list-style: none;
    margin: 0;
    padding: 0;
  }
  nav ul li {
    margin: 0;
  }
  nav ul li a {
    color: white;
    text-decoration: none;
  }
  nav ul li a:hover {
    text-decoration: underline;
  }

  .router-link-active {
    color: rgb(56, 205, 173);
    border: 1px solid white;
    padding: 10px;
  }
</style>