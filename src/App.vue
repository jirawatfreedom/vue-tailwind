<template>
  <div id="app" class="bg-gray-200 antialiased">
    <header class="bg-gray-900">
    </header>
    <section class="bg-gray-800">
      <input type="text" value="" name="" id="" placeholder="Search by keyword"/>  
      <button>Filters</button>
    </section>
    <main>

      <h3>Los Angeles</h3>
      <p>Live like the stars in these luxurious Southern California estates.</p>
    </main>
    <router-view/>
  </div>
</template>
<script charset="utf-8">
export default {
  name: 'app',
  components:{}
}
</script>
<style type="text/css" src="./assets/css/tailwind.css">
  
</style>
