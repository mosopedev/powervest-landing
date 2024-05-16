<template>
  <div>
    <Navbar />
    <p class="intro-grn">
      Looking for the most affordable way to start harnessing the power of the
      sun?
    </p>
    <h1 class="heading-text">
      We're building Africa's first consumption&NoBreak;-&NoBreak;based finance
      platform for solar energy.
    </h1>
    <!-- <p class="cta">
      Since you are here, join our waitlist to get notified when we launch!
    </p> -->

    <!-- <div class="form-sect">
      <input type="email" class="inpt" placeholder="Email address" />
      <button>Submit</button>
    </div> -->

    <div class="mockup-sect">
      <img
        src="/images/app-mockup.svg"
        class="app-mockup"
        alt=""
      />
    </div>
  </div>
</template>

<script setup>
import Navbar from "../components/navbar.vue";
</script>

<style scoped>
.intro-grn {
  width: 40%;
  margin: 5vh auto 40px;
  text-align: center;
  font-weight: 600;
  font-size: 20px;
  color: #2bb930;
}
.heading-text {
  width: 75%;
  margin: auto;
  font-family: "Urbanist";
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  text-align: center;
  letter-spacing: -1.15556px;
  color: #1a1a1a;
}
.cta {
  width: 40%;
  margin: 5vh auto 40px;
  text-align: center;
  font-weight: 600;
  font-size: 22px;
  color: #2bb930;
}
.form-sect {
  margin: 10px auto 0;
  width: 80%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.form-sect button {
  height: 50px;
  background: #2bb930;
  width: 120px;
  margin-left: 15px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  color: #fff;
  font-weight: 600;
  font-size: 18;
}
.inpt {
  border: 1px solid #d2d2d2;
  outline: none;
  height: 50px;
  width: 300px;
  font-size: 16px;
  padding-left: 15px;
  border-radius: 6px;
}
.mockup-sect {
  width: 100%;
  margin-top: 6vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
.app-mockup {
  width: 60%;
  margin: auto 0;
}

@media screen and (max-width: 1200px) {
  .heading-text {
    width: 80%;
    font-size: 50px;
  }
}

@media screen and (max-width: 1000px) {
  .heading-text {
    width: 80%;
    font-size: 45px;
  }
  .cta {
    width: 60%;
    font-size: 20px;
  }
}

@media screen and (max-width: 800px) {
  .heading-text {
    margin-top: 10vh;
    width: 80%;
    font-size: 35px;
  }
  .cta {
    width: 60%;
    font-size: 18px;
  }
  .mockup-sect {
    display: none;
  }
  .form-sect {
    margin-top: 10vh;
    flex-direction: column;
  }
  .inpt {
    width: 100%;
  }
  .form-sect button {
    margin-top: 20px;
    width: 100%;
    margin-left: 0px;
    font-size: 16px;
  }
}

@media screen and (max-width: 500px) {
  .heading-text {
    width: 90%;
    font-size: 32px;
  }
  .cta {
    width: 70%;
  }
}
</style>
