<!--
Testing a comment first
-->

<div class="logo-text">
  <img src="/assets/Main-Logo.jpg" alt="My Logo">

  <div class="welcome-text">
    <h1>Welcome</h1>
    <p>We serve coffee popcycles.</p>
    <p>They're delicious.</p>
    <p>Delivered with care.</p>
  </div>
</div>

<style>
.logo-text {
  min-height: 65vh;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 40px;
}

.logo-text img {
  width: 450px;
  height: auto;
}

.welcome-text {
  flex: 0 1 auto;
}

@media (max-width: 600px) {
  .logo-text {
    min-height: auto;
    flex-direction: column;
    text-align: center;
    padding: 40px 20px;
  }

  .logo-text img {
    width: 250px;
  }
}
</style>


