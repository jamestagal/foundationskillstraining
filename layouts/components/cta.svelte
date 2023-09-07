<script>
    export let title, description, link, image, shape;
</script>
<!-- cta area -->
<div class="cta-area py-120">
  <div class="container">
    <div class="cta-wrapper">
      <div class="cta-arrow-shape">
        <img src="{shape.url}" alt="{shape.alt}" />
      </div>
      <div class="row align-items-center">
        <div class="col-lg-7">
          <div class="cta-content">
            <h2>
              {title}
            </h2>
            <p>
              {description}
            </p>
            <a href="{link.url}" class="cta-btn">{link.title}</a>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="cta-img">
            <img src="{image.url}" alt="{image.alt}" />
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- cta area end -->
