<template>
  <div class="hero-section">
    <nav>
      <div class="topbar">
        <p>
          Email: vuevitriol@Codex.com &nbsp; &nbsp; Phone: +234 (0) 908 6797 871
        </p>
      </div>
      <div class="navbar">
        <div class="logo">
          <h1>!Vitriol</h1>
        </div>
        <div class="nav-link">
          <ul class="navs">
            <li class="nav" id="nav">Home</li>
            <li class="nav" id="nav">About</li>
            <li class="nav" id="nav">Latest Course</li>
            <li class="nav" id="nav">Social Events</li>
            <li class="nav" id="nav">Blogs</li>
            <li class="nav" id="nav">Contact</li>
            <li class="nav"><button>Connect Wallet</button></li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="section-hero">
      <div class="section-grid">
        <div class="hero-text">
          <h1 class="Give">GIVE A HAND TO MAKE THE BETTER WORLD</h1>
          <br />
          <p class="sea">
            The sea freight service has grown conside rably in recent years. We
            spend timetting to know your processes to. inappropriate behavior is
            often laughed off as “boys will be boys,” women face higher conduct
            especially workplace.
          </p>
          <br />
          <div class="hero-buttons">
            <div class="buttons">
              <button class="button1">Explore</button>
            </div>
            <div class="buttons">
              <button class="button2">Contact Us</button>
            </div>
          </div>
        </div>

        <div class="hero-box">
          <div class="box">
            <div class="charity-box">
              <h2>Vitriol Charity Funds</h2>
              <br />
              <b> <p>Be the light to the world while you can.</p></b>
            </div>
            <div class="amount">
              <label>Amount to give </label>
              <br />
              <input
                type="number"
                id="input"
                placeholder="Enter Amout To Give"
              />
              <br />

              <div class="button3">
                <button class="submit">Make Donation</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderNew",
  meta: {
    title: "Header",
  },
};
</script>

<style scoped>
@import "../assets/css/Header.css";
</style>