<script>
  export let title1, title2, subtitle, trainer1, trainer2, trainer3, trainer4;
</script>

<!-- instructor-area -->
<div class="instructor-area py-120">
  <div class="container">
    <div class="row">
      <div class="col-lg-6 mx-auto">
        <div class="site-heading text-center">
          <h2 class="site-title">{title1} <span>{title2}</span></h2>
          <p>
            {subtitle}
          </p>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-6 col-lg-4 col-xl-3">
        <div class="instructor-item">
          <div class="instructor-img">
            <a href="."><img src={trainer1.src} alt={trainer2.alt} /></a>
          </div>
          <div class="instructor-content">
            <span class="instructor-tag">{trainer1.title}</span>
            <a href="." class="d-block"
              ><h5 class="instructor-name">{trainer1.name}</h5></a
            >
            <div class="instructor-social">
              <a href="."><i class="fab fa-facebook-f" /></a>
              <a href="."><i class="fab fa-twitter" /></a>
              <a href="."><i class="fab fa-instagram" /></a>
              <a href="."><i class="fab fa-linkedin-in" /></a>
              <a href="."><i class="fab fa-behance" /></a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 col-xl-3">
        <div class="instructor-item">
          <div class="instructor-img">
            <a href="."><img src={trainer2.src} alt={trainer2.alt} /></a>
          </div>
          <div class="instructor-content">
            <span class="instructor-tag">{trainer2.title}</span>
            <a href="." class="d-block"
              ><h5 class="instructor-name">{trainer2.name}</h5></a
            >
            <div class="instructor-social">
              <a href="."><i class="fab fa-facebook-f" /></a>
              <a href="."><i class="fab fa-twitter" /></a>
              <a href="."><i class="fab fa-instagram" /></a>
              <a href="."><i class="fab fa-linkedin-in" /></a>
              <a href="."><i class="fab fa-behance" /></a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 col-xl-3">
        <div class="instructor-item">
          <div class="instructor-img">
            <a href="."><img src={trainer3.src} alt={trainer3.alt} /></a>
          </div>
          <div class="instructor-content">
            <span class="instructor-tag">{trainer3.title}</span>
            <a href="." class="d-block"
              ><h5 class="instructor-name">{trainer3.name}</h5></a
            >
            <div class="instructor-social">
              <a href="."><i class="fab fa-facebook-f" /></a>
              <a href="."><i class="fab fa-twitter" /></a>
              <a href="."><i class="fab fa-instagram" /></a>
              <a href="."><i class="fab fa-linkedin-in" /></a>
              <a href="."><i class="fab fa-behance" /></a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4 col-xl-3">
        <div class="instructor-item">
          <div class="instructor-img">
            <a href="."><img src={trainer4.src} alt={trainer4.alt} /></a>
          </div>
          <div class="instructor-content">
            <span class="instructor-tag">{trainer4.title}</span>
            <a href="." class="d-block"
              ><h5 class="instructor-name">{trainer4.name}</h5></a
            >
            <div class="instructor-social">
              <a href="."><i class="fab fa-facebook-f" /></a>
              <a href="."><i class="fab fa-twitter" /></a>
              <a href="."><i class="fab fa-instagram" /></a>
              <a href="."><i class="fab fa-linkedin-in" /></a>
              <a href="."><i class="fab fa-behance" /></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- instructor-area end -->
<style>
  a {
    text-decoration: none;
  }
</style>
