<template>
    <div class="container">
        <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="">
        <img src="@/assets/logo.jpg" width="112" height="28">
      <!-- <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28"> -->
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
        <div class="control">
            <input class="input" type="text" placeholder="We have everything thats on your mind">
        </div>
        <div class="control">
            <a class="button is-light">
            Search
            </a>
        </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-primary">
            <strong>Sign up</strong>
          </a>
          <a class="button is-light">
            Log in
          </a>
        </div>
      </div>
    </div>
  </div>
</nav>
    </div>
</template>