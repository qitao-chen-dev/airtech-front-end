<template>
  <div class="index">
    <div class="airtech-logo">
      <img src="../assets/airtech-logo.png" alt="" />
    </div>
    <div class="welcome-content">
      <div class="welcome-words">
        <h1>Welcome</h1>
        <p>
          Since our opening, we have become masters of our craft. our commitment
          to quality products, exceptional services and incomparable customer
          care keep our community coming back again and again.
        </p>
        <div class="contact-info">
          <address>
            <a href="mailto:eric.chen.dev@outlook.com"
              >Email:eric.chen.dev@outlook.com</a
            >
          </address>
          <a href="tel:0415366181">Mobile:0415366181</a>
        </div>
        <div class="subscribe">
          Subscribe to our mailing list
          <div class="subscribe-area">
            <input type="text" placeholder="Enter your email here*" />
            <button>JOIN</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>
<style lang="less" scoped>
* {
  padding: 0;
  margin: 0;
}

// html,
// body {
//   font-family: Arial, Helvetica, sans-serif;
//   height: 100%;
// }

.index {
  display: flex;
  height: 100%;
  width: 100%;
  overflow: hidden;
}

.airtech-logo {
  background: rgb(3, 50, 73);
  width: 50%;
  height: 100%;
  flex: 1 1 auto;
}

.airtech-logo img {
  object-fit: cover;
  width: 100%;
  height: 100%;
}

.welcome-content {
  background: rgb(255, 128, 56);
  flex: 1 1 auto;
  width: 50%;
  position: relative;
}

.welcome-content .welcome-words {
  box-sizing: border-box;
  height: 100%;
  width: 100%;
  padding: 100px 50px 100px 50px;
}

.welcome-content h1 {
  position: absolute;
  top: 2.5em;
  font-size: 50px;
}

.welcome-content p {
  position: absolute;
  top: 12em;
  font-size: 22px;
}

.welcome-content .contact-info a {
  position: absolute;
  font-size: large;
  color: black;
  text-decoration: none;
  cursor: pointer;
  top: 39em;
}

.welcome-content .contact-info address a {
  top: 37em;
}

.welcome-content .subscribe {
  font-size: large;
  position: absolute;
  top: 45em;
  width: calc(100% - 100px);
}

.welcome-content .subscribe .subscribe-area {
  margin-top: 1em;
  width: 100%;
  height: 3em;
}

.welcome-content .subscribe .subscribe-area input,
button {
  border: none;
  background-image: none;
  background-color: transparent;
  -webkit-box-shadow: none;
  -moz-box-shadow: none;
  box-shadow: none;
  outline: none;
}

.welcome-content .subscribe .subscribe-area input {
  font-size: large;
  padding: 5px;
  width: 80%;
  height: 100%;
  border: 2px solid black;
  border-radius: 5px;
  box-sizing: border-box;
}

.welcome-content .subscribe .subscribe-area button {
  cursor: pointer;
  margin-left: 1em;
  width: 15%;
  height: 100%;
  border: 1px solid black;
  background-color: black;
  color: white;
}

.welcome-content .subscribe .subscribe-area input:focus {
  background: rgba(3, 50, 73, 0.2);
  color: white;
}
</style>
