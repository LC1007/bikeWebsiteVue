<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">Bikes</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item">
                    <router-link class="p-3 text-decoration-none" to="/">Home</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="p-3 text-decoration-none" to="/products">Products</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="p-3 text-decoration-none" to="/contact">Contact</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="p-3 text-decoration-none" to="/about">About</router-link>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>