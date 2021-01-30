<template>
  <div class="bg">
    <section class="player">
      <div class="container">
        <div class="border-top"></div>
        <div class="text">
          <h1>ASTRID</h1>
          <h4>Glaive</h4>
        </div>
        <div class="time">
          <a href="#">0:00</a>
          <a href="#">1:41</a>
        </div>
        <div class="seek">
          <div class="fill"></div>
          <div class="handle"></div>
        </div>
      </div>
      <button>PLAY THE SONG</button>
    </section>
  </div>
</template>
<style lang="css" scoped>
.bg {
  background: url("https://images.genius.com/a32a192bea38206e22da4293cdcfc0f7.1000x1000x1.jpg")
    no-repeat center center/cover;
  height: 100vh;
  width: 100vw;
}

.player {
  width: 400px;
  height: 370px;
  position: absolute;
  top: 45%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: rgba(255, 255, 255, 0.1);
  border-radius: 10px;
  margin: 10px 0 0 0;
  box-shadow: 3px 3px 50px rgba(0, 0, 0, 0.5), -3px -3px 50px rgba(0, 0, 0, 0.5);
}

.container {
  width: 90%;
  margin: 0 auto;
  overflow: hidden;
}

.border-top {
  border-top: 3px solid #fff;
  border-radius: 50%;
  margin-top: 30px;
}

.text {
  text-align: center;
  margin: 10px 0;
}
.text h1 {
  font-size: 3em;
  color: #39ff14;
}
.text h4 {
  font-size: 1.4em;
  color: white;
}
.time {
  display: flex;
  justify-content: space-between;
  margin: 20px 0 0 0;
}
.time a {
  color: #fff;
  font-size: 1.1em;
  text-decoration: none;
  font-weight: bold;
}
.seek {
  width: 100%;
  height: 4px;
  background: rgba(255, 255, 255, 0.3);
  margin: 5px 0;
  position: relative;
}
.fill {
  width: 65%;
  height: 4px;
  background: rgba(255, 255, 255, 0.7);
}
.handle {
  width: 10px;
  height: 10px;
  background: rgba(255, 255, 255, 0.8);
  border-radius: 50%;
  position: absolute;
  top: -3px;
  right: 120px;
}
button {
  color: #fff;
  margin-top: 20px;
  font-size: 1.8em;
  font-weight: bold;
  text-align: center;
  background: #00c9d0;
  border: none;
  width: 100%;
  height: 70px;
  border-bottom-left-radius: 10px;
  border-bottom-right-radius: 10px;
  cursor: pointer;
  transition: all 0.3s ease-in-out;
}
button:hover {
  background: #02a0a5;
}
.logo-1 {
  color: white;
  animation: neon 3s infinite;
}
</style>
