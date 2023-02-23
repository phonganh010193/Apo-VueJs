<template>
    <div class="container-fluid top-container">
        <div class="container navbar-header">
            <ul>
                <li>SignIn</li>
                <li>SignOut</li>
            </ul>
            <div class="user-logo">
                <img src="https://discover.garmin.com/vi-VN/instinct/instinct-onepiece/images/onepiece-kv-luffy.png" alt="" />
                <span>User Name</span>
            </div>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style>
    .top-container {
    height: 50px;
    border-bottom: 1px solid rgb(185, 185, 185);
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  }

  .navbar-header{
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }

  .navbar-header ul {
    display: flex;
    flex-direction: row;
    justify-content: start;
    padding: 0;
    margin: 0;
  }

  .navbar-header ul li {
    list-style: none;
    width: 100px;
    height: 50px;
    line-height: 50px;
    text-align: center;
    border-left: 1px solid gray;
  }

  .navbar-header ul li:hover {
    color: #41b883;
  }

  .navbar-header ul li:last-child{
    border-right: 1px solid gray;
  }
</style>