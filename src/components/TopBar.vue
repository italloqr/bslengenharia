<template>
  <div id="#" class="top-menu">
    <div class="top-menu-logo-link">
      <a href="https://bslengenharia.com.br" class="logo-link">
        <img src="../assets/img/logo.jpeg" loading="lazy" width="90" height="90">
      </a>
    </div>
    <div class="top-menu-navigation">
      <nav class="top-menu-navigation-container" aria-label="Main" role="navigation">
        <ul class="top-menu-navigation-list">
          <li class="top-menu-list-item">
            <a href="#">About</a>
          </li>
          <li class="top-menu-list-item"><a href="#">Testimonials</a></li>
          <li class="top-menu-list-item"><a href="#">FAQs</a></li>
          <li class="top-menu-list-item"><a href="#">Methods</a></li>
          <li class="top-menu-list-item"><a href="#">Resources</a></li>
          <li class="top-menu-list-item"><a href="#">Contact</a></li>
        </ul>	
      </nav>
    </div>
    <div>
      <a href="#" class="top-menu-action-button">
        <button>
          Schedule&nbsp;Consultation
        </button>
      </a>
    </div>
  </div>
</template>
<style>
.top-menu {
  display: flex;
  padding: 20px;
  align-content: center;
  justify-content: space-between;
  background: #ffffff;
}
.top-menu-navigation {
  margin-top: 20px;
}
.top-menu-navigation-list {
  align-items: center;
  display: flex;
  justify-content: flex-start;
  width: 100%;
  align-items: center;
}

.top-menu-list-item {
  margin-right: 20px;
}

.top-menu-action-button {
  display: flex;
  margin-top: 27px;
}
</style>