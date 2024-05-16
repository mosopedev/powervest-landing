<template>
  <div class="navbar-container">
    <img
      src="/images/powervest-full-logo.svg"
      class="nav-logo"
      alt="Powervest Logo"
    />

    <!-- <div class="navbar-rhs">
            <p>Follow us via</p>
            <div class="socials">
                <div class="social">
                    <img src="/icons/linkedin.svg" class="social-icon" alt="">
                </div>
            </div>
        </div> -->
  </div>
</template>

<script setup></script>

<style scoped>
.nav-logo {
  width: 180px;
}
.navbar-container {
  height: 80px;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 60px;
}
.navbar-rhs {
  display: flex;
  align-items: center;
}
.nav-items {
  margin-right: 30px;
}
.nav-items a {
  font-size: 16px;
  color: #818181;
  margin: 0 15px;
}
.nav-items a.active {
  color: #000;
  font-weight: 500;
}
.green-round-btn {
  font-size: 16px;
  font-weight: 600;
}
@media screen and (max-width: 700px) {
  .navbar-container {
    padding: 0 20px;
  }
}
</style>
