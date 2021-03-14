<template>
  <div>
    <div
      class="w-full flex items-center justify-center bg-cover bg-center text-5xl text-white font-bold"
      style="
        height: 500px;
        background-image: url(https://picsum.photos/seed/picsum/1500/500);
      "
    >
      <!-- <img
        src="https://picsum.photos/seed/picsum/1500/500"
        class="object-cover h-full w-full"
      /> -->
      <h1>Niki's Illustrations</h1>
    </div>
    <ImageGrid></ImageGrid>
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
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
} */

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
