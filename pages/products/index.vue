<template>
    <section class="container">
        <h1>Product Index Page</h1>
        <ol>
            <li>
                <nuxt-link to="/products/1">Product 1</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/products/2">Product 2</nuxt-link>
            </li>
        </ol>
    </section>
</template>


<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  flex-direction: column;
}
.container ol li {
    list-style-type: none;
}
</style>