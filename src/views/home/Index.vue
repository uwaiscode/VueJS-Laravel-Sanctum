<template>
  <div class="home">
    <main>
      <div class="px-4 pt-5 my-5 text-center border-bottom">
        <h1 class="display-4 fw-bold">Uwais Code</h1>
        <div class="col-lg-6 mx-auto">
          <p class="lead mb-4">
            Ujicoba pembuatan auth dengan laravel sanctum
          </p>
          <p>
            <router-link
              :to="{ name: 'login' }"
              v-if="!loggedIn"
              class="btn btn-primary my-2 my-sm-0"
              >LOGIN</router-link
            >
          </p>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>