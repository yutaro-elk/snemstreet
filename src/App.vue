<template>
  <div id="app">
    <div class="wall">
      <h1>
        <div class="huti">SNEM Street</div>
        <div class="naka">SNEM Street</div>
      </h1>
      <span class="red font1 abs" style="top:3vw;left:3vw">NEM!</span>
      <span class="nem font2 abs">NEM</span>
      <span class="red font2 abs" style="top: 5vw;left: 35vw;transform: rotate(-30deg);">
        FUD!<br>FUD!<br>FUD!
      </span>
      <div class="nem font2 fz5 abs">NEM</div>
      <div class="vintage font3 abs">SNEMS</div>
    </div>
  </div>
</template>

<script>

</script>

<style>

body {
  /* overscroll-behavior: none; */
  background-image: url(static/bg1.jpg);
  /* background-position: center center; */
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-color: #1a1a1a;

  /* overflow: none; */
}

h1 {
  margin: 40px;
  margin-left: 100px;
  /* transform: rotate(-30deg); */
}

.huti {
  position: absolute;
  top: 3vw;
  left: 3vw;
  font-family: "Sedgwick Ave Display", cursive;
  font-size: 7vw;
  mix-blend-mode: overlay;
  text-shadow: 
    5px 5px 1px #000, 
    -5px 5px 1px #000, 
    5px -5px 1px #000,
    -5px -5px 1px #000;
  /* mix-blend-mode: overlay; */
}

.naka {
  position: absolute;
  top: 3vw;
  left: 3vw;
  font-family: "Sedgwick Ave Display", cursive;
  font-size: 7vw;
  color: rgba(255, 255, 255, 0.438);
  text-shadow: 
    0px 0px 3px rgba(248, 242, 242, 0.863),
    5px 5px 40px rgba(207, 16, 16, 0.562);
  /* color: aliceblue */
}

.font1 {
  font-family: "Gloria Hallelujah", cursive;
}

.font2 {
  font-family: "Permanent Marker", cursive;
}

.font3 {
  font-family: "Gochi Hand", cursive;
}

.font4 {
  font-family: "Caveat Brush", cursive;
}

.abs {
  position: absolute;
}

.red {
  filter: blur(1.5px);
  font-size: 4vw;
  line-height: 4vw;
  color: lighten(red, 1%);
}

.black {
  filter: blur(1.5px);
  font-size: 3vw;
  color: black;
}

.vintage {
  filter: contrast(500%) blur(1.5px);
  font-size: 5vw;
  color: lighten(tomato, 1%);
  text-shadow: 4px 3px 1px #fff, 9px 8px 0px rgba(0, 0, 0, 1);
  display: inline-block;
  transform: rotate(-7.5deg);
}

.nem {
  filter: blur(1.5px);
  font-size: 5vw;
  color: #00d1ff;
  text-shadow: 4px 3px 1px #fff, 4px 3px 1px #fff, 4px 3px 1px #fff,
    4px 3px 1px #fff, 9px 8px 0px #00a836, -4px -5px 0px #00a836,
    12px -2px 0px #00a836, -4px 6px 0px #00a836, 9px 8px 0px #00a836;
  display: inline-block;
  transform: rotate(-7.5deg);
}
</style>
