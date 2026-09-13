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
  display: flex;
  align-items: center;
  gap: 40px;
}

.logo-text img {
  width: 350px;
  height: auto;
}

.welcome-text {
  flex: 1;
}

@media (max-width: 600px) {
  .logo-text {
    flex-direction: column;
    text-align: center;
  }

  .logo-text img {
    width: 250px;
  }
}
</style>

