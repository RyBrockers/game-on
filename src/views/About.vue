<template>
  <div class="about">
    <div>
      <h1 class="ta-center">About TheryBrock!</h1>
    </div>
    <div class="container-info">
      <div class="copy">
        <h2>A little bit about me</h2>
        <p>
          Hey Team! First of all I would like to thank you if you have gotten
          this far on my website. It means a hell of a lot to me the support I
          recieve from the wonderful gaming community.
        </p>
        <p>
          My name is Ryan and I am 36 years old. My first experience with gaming
          was when my parents bought me an Amiga 600 for Christmas when I was 10
          years old. I remember playing games like Cannon Fodder, Pushover,
          Brutal Sports Football and Flashback!.
        </p>
        <p>
          After practically owning most consoles and cuurently playing a PS5. I
          can safely admit I am true video gaming fan!
        </p>
        <p>
          I am also obviously interested in technology and currently record,
          edit and post all my own videos. I am truly enjoying the learning
          curve I find my self now upon. Any feedback in the comments on the
          videos would be much appreciated.
        </p>
        <p>
          I do have a full time day job. I am a front-end web developer for a
          well know clothing retailer. All the spare time and effort I get goes
          into this website and the Twitch and Youtube content I create. GAME ON!
        </p>
      </div>
      <div class="images">
        <div class="profile-image">
          <img
            src="../../src/assets/amiga-image.jpg"
            alt="amiga games images"
          />
          <div class="ta-center">Some Amiga classics</div>
        </div>
        <div class="profile-image">
          <img src="../../src/assets/fave-games.jpg" alt="" />
          <div class="ta-center">Some of my favourite games</div>
        </div>
      </div>
    </div>

    <div class="container-gear">
      <div class="title">
        <h2 class="ta-center">Lets talk about gear!</h2>
      </div>
      <div class="gear">
        <div class="container-info">
              <div class="images">
            <div class="profile-image">
              <img
                src="../../src/assets/setup-image.jpg"
                alt="amiga games images"
              />
              <div class="ta-center">My Setup</div>
            </div>
            <div class="profile-image">
              <img src="../../src/assets/Stream-software.jpg" alt="" />
              <div class="ta-center"><a href="https://streamlabs.com/" target="blank">StreamLabs</a>, <a href="https://www.adobe.com/uk/" target="blank">Adobe</a></div>
            </div>
          </div>
          <div class="copy">
            <h2>My PC SPECS!</h2>
            <p>
              Hey Team! I have bought and built my own PC recently. With monitor
              and keyboard it came to a little under £1,500. Here is a list of
              specs below.
            </p>
            <div class="list">
              <ul>
                <li>EVGA Geforce RTX 2060 super</li>
                <li>Ryzen 3600 overclocked</li>
                <li>Sabrent 256g m.2 drive</li>
                <li>Seagate 1tb HDD</li>
                <li>MSI B450 Pro gaming carbon motherboard</li>
                <li>EVGA 650 BQ 80+ Bronze power suplly</li>
                <li>Asus TUF VG289Q 28 inch 4k gaming monitor</li>
                <li>SteelSeries APEX 7 mecahnical Keyboard</li>
              </ul>
            </div>
            <h2>Streaming Softwear</h2>
            <p>I use free software for streaming.</p>
            <ul>
              <li>OBS Studio</li>
              <li>StreamLabs OBS</li>
              <li>Twitch streamers dashboard</li>
              <li>Elgato capture software</li>
            </ul>
            <h2>Video Editing</h2>
            <p>I use a paid Adobe account.</p>
            <ul>
              <li>Adobe PhotoShop</li>
              <li>Adobe AfterEffects</li>
              <li>Adobe Premier Pro</li>
            </ul>
          </div>
      
        </div>
      </div>
      <div class="container-action">
        <h2 class="ta-center">Click below to get in on the action now!</h2>
      </div>
      <div class="stream-icons">
        <div class="youtube">
          <a href="https://www.youtube.com/channel/UC-bbkuggI11O9HLqBw6KXTA" target="blank"><i class="fab fa-youtube"></i></a>
        </div>
        <div class="twitch">
          <a href="https://www.twitch.tv/therybrock" target="blank"><i class="fab fa-twitch"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.about {
  font-family: "Roboto", sans-serif;
}
.container-info {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  margin-top: 50px;
  padding: 10px;
}
.copy {
  width: 100%;
  max-width: 40%;
  padding: 10px;
  background: #f7ffe0;
}
.profile-image div {
  padding: 10px;
}
.stream-icons {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
}

.fa-youtube {
  color: #ed3833;
  font-size: 100px;
  margin: 0 20px 0 20px;
}
.fa-twitch {
  color: #924cf7;
  font-size: 100px;
  margin: 0 20px 0 20px;
}
img {
  padding: 20px;
}
a {
  text-decoration: none;
}
.container-action {
  margin-top: 100px;
}

@media only screen and (max-width: 600px) {
.copy {
  width: 100% !important;
  max-width: 100% !important;
  margin: 0;
}

.container-info {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 50px;
  padding: 10px;
  width: 100%;
} 
.profile-image img {
width: 100%;
margin: 0;
padding: 0;
}
.stream-icons {
  margin: 0;
}
}
</style>