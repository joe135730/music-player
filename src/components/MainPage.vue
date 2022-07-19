<template>
<div class="musicPlayerWrapper">
  <div class="musicMain">
    <div class="musicLeftNavbar">
      <div class="leftNavbarTop">
        <div class="musicLogo">
          <div class="logo"></div>
          <p>Music Box</p>
        </div>
        <div class="musicCategory">
          <ul>
            <li>
              <div class="icon"></div>
              <p>Home</p>
            </li>
            <li>
              <div class="icon"></div>
              <p>Discover</p>
            </li>
            <li>
              <div class="icon"></div>
              <p>Radio</p>
            </li>
          </ul>
        </div>
      </div>
      <div class="leftNavbarMiddle"></div>
      <div class="leftNavbarBottom"></div>
    </div>
    <div class="musicContent"></div>
    <div class="musicRightNavbar"></div>
  </div>

  <div class="musicFooter"></div>

</div>

</template>

<script setup>

</script>

<style scoped>
.musicLogo {

}

.musicCategory {

}

li {
  display: flex;
}

.icon {
  width: 20px;
  height: 20px;
  margin-right: 6px;
  background: #000;
}

</style>
