<template>
    <topbar-risgiter />
    <topbar-logo />
    <topbar-nav />
</template>

<script>
import TopbarRisgiter from './components/TopbarRisgiter.vue';
import TopbarLogo from './components/TopbarLogo.vue';
import TopbarNav from './components/TopbarNav.vue';
export default {
    components: {
        TopbarRisgiter,
        TopbarLogo,
        TopbarNav
    }
}
</script>
<style>
  /* navbar-header-left */
  
  
  /* logo-user */

  .user-logo {
    height: 50px;
  }
  .user-logo img {
    width: 40px;
    height: 40px;
    border-radius: 20px;
    margin-right: 5px;
  }

  /* transport */

  .logo-shop {
    display: flex;
    flex-direction: row;
  }

  .logo-shop img {
    width: 150px;
    height: 150px;
  }

  .item-content img{
    width: 50px;
    height: 50px;
    border-radius: 25px;
  }

  .icon-cart {
    width: 50px;
    height: 50px;
    background-color: #198754;
    text-align: center;
    line-height: 50px;
    border-radius: 25px;
    margin-right: 10px;
  }

  .item-content {
    display: flex;
    flex-direction: row;
    align-items: center;
  }

  .shop-content {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 100%;
  }

  .navbar-container {
    margin: 0;
    padding: 0;
    height: 50px;
    background-color: black;
  }

  .navbar-content ul li {
    list-style: none;
    border-left: 1px solid gray;
    height: 50px;
    width: 150px;
    line-height: 50px;
    text-align: center;
  }

  .navbar-content ul li:last-child{
    border-right: 1px solid gray;
  }

  .navbar-content ul li a {
    text-decoration: none;
    color: white;
  }

  
</style>