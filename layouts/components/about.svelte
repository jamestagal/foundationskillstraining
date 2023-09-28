<script>
  export let title1, title2, title3, description, image, feature1, feature2, link; 
</script>
<div class="about-area py-120">
  <div class="container">
    <div class="row align-items-center">
      <div class="col-lg-6">
        <div class="about-left">
          <div class="about-img">
            <img src="{image.src}" alt="{image.altText}" />
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="about-right">
          <div class="site-heading mb-3">
            <h2 class="site-title">
              {title1} <span>{title2}</span> {title3}
            </h2>
          </div>
          <p class="about-text">
            {description}
          </p>
          <div class="about-list-wrapper">
            <ul class="about-list list-unstyled">
              <li>
                <div class="icon"><i class="fal fa-user-friends" /></div>
                <div class="text">
                  <h4>{feature1.title}</h4>
                  <p>{feature1.subtitle}</p>
                </div>
              </li>
              <li>
                <div class="icon"><i class="fal fa-headset" /></div>
                <div class="text">
                  <h4>{feature2.title}</h4>
                  <p>{feature2.subtitle}</p>
                </div>
              </li>
            </ul>
          </div>
          <a href="{link.url}" class="theme-btn"
            >{link.text} <i class="far fa-arrow-right" /></a
          >
        </div>
      </div>
    </div>
  </div>
</div>
<!-- about area end -->
