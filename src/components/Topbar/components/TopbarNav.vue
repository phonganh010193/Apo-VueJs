<template>
    <div class="container-fluild navbar-container">
      <div class="container d-flex flex-row align-items-center justify-content-between">
        <div class="navbar-content">
          <ul class="d-flex flex-row align-items-center m-0 p-0 ">
            <li>
              <a href="#">HOME PAGE</a>
            </li>
            <li>
              <a href="#">INTRODUCE</a>
            </li>
            <li>
              <a href="#">PRODUCT</a>
            </li>
            <li>
              <a href="#">CONTACT</a>
            </li>
            <li>
              <a href="#">NEW SERVICES</a>
            </li>
          </ul>
          
        </div>
        <div class="search-content">
          <div class="input-group">
            <div class="form-outline">
              <input type="search" id="form1" class="form-control" />
            </div>
            <button type="button" class="btn btn-primary">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
              </svg>
            </button>
          </div>
        </div>
      </div>
    </div>
</template>
<script>
    export default {

    }
</script>
<style>
    .input-group {
        height: 50px;
        align-items: center;
    }

    .search-content {
        width: 300px;
    }
</style>