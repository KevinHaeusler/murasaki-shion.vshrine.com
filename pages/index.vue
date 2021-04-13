<template>
  <div class="w-screen bg-accent pb-5">
    <div class="mx-auto max-w-screen-lg">
      <h1 class="text-primary text-center font-bold text-5xl">
        <span>Murasaki</span> <span class="text-primary-dark">Shion</span>
        <span class="text-secondary">Virtual</span>
        <span class="text-white">Shrine</span>
      </h1>
      <p class="text-black text-center mt-5">
        This website is a work in progress, feel free to checkout the
        <a href="https://github.com/KevinHaeusler/minato-aqua.vshrine.com"
          >Github</a
        >
      </p>
      <div class="lg:flex mt-5 lg:place-content-center">
        <div class="w-40 h-40 mr-5 bg-primary text-white text-center shadow">
          Primary
        </div>
        <div
          class="w-40 h-40 mr-5 bg-primary-dark text-white text-center shadow"
        >
          Primary Dark
        </div>
        <div class="w-40 h-40 mr-5 bg-secondary text-white text-center shadow">
          Secondary
        </div>
        <div class="w-40 h-40 mr-5 bg-accent text-black text-center shadow">
          Accent
        </div>
        <div class="w-40 h-40 mr-5 bg-white text-black text-center shadow">
          White
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
