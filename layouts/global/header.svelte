<header class="header">
  <div class="main-navigation">
    <nav class="navbar navbar-expand-lg fixed-top">
      <div class="container">
        <a class="navbar-brand" href=".">
          <img
            src="logo.png"
            width="375"
            height="74"
            alt="Foundation Skills Training logo"
          />
        </a>
        <div class="mobile-menu-right">
          <a href="." class="mobile-search-btn search-box-outer"
            ><i class="far fa-search" /></a
          >
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#main_nav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"><i class="far fa-bars" /></span>
          </button>
        </div>
        <div class="collapse navbar-collapse" id="main_nav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href=".">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="aboutus">About Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="blog">Blog</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="contactus">Contact</a>
            </li>
          </ul>
          <div class="header-nav-right">
            <div class="header-btn-area">
              <!-- <a href="." class="header-btn-text">Sign In</a> -->
              <a href="." class="header-btn">Get Started</a>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</header>

<style>
  .navbar.fixed-top {
    background: #fff;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.17);
    animation: slide-down 0.7s;
  }
  @keyframes slide-down {
    0% {
      transform: translateY(-100%);
    }
    100% {
      transform: translateY(0);
    }
  }
  .navbar.fixed-top .nav-item .nav-link::before {
    color: #00235a;
  }
</style>
