<template>
  <topbar />
  <div class="container">
    <sidebar />
  </div>
</template>
<script>
import Topbar from './components/Topbar/Topbar.vue';
import Sidebar from './components/Sidebar/Sidebar.vue';
export default {
  components: {
    Topbar,
    Sidebar
  }

}
</script>


