<script>
  export let title1, title2, subtitle, student1, student2;
</script>

<!-- testimonial-area -->
<div class="testimonial-area bg py-120">
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
    <div class="testimonial-slider owl-carousel owl-theme">
      <div class="testimonial-single">
        <div class="testimonial-quote">
          <span class="testimonial-quote-icon"
            ><i class="fal fa-quote-right" /></span
          >
          <p>
            {student1.quote}
          </p>
        </div>
        <div class="testimonial-content">
          <div class="testimonial-author-img">
            <img src={student1.image.src} alt={student1.image.altText} />
          </div>
          <div class="testimonial-author-info">
            <h4>{student1.name}</h4>
            <p>{student1.title}</p>
            <div class="testimonial-rate">
              <i class="fas fa-star" />
              <i class="fas fa-star" />
              <i class="fas fa-star" />
              <i class="fas fa-star" />
              <i class="fas fa-star" />
            </div>
          </div>
        </div>
      </div>
      <div class="testimonial-single">
        <div class="testimonial-quote">
          <span class="testimonial-quote-icon"
            ><i class="fal fa-quote-right" /></span
          >
          <p>
            {student2.quote}
          </p>
        </div>
        <div class="testimonial-content">
          <div class="testimonial-author-img">
            <img src={student2.src} alt={student2.altText} />
          </div>
          <div class="testimonial-author-info">
            <h4>{student2.name}</h4>
            <p>{student2.title}</p>
            <div class="testimonial-rate">
              <i class="fas fa-star" />
              <i class="fas fa-star" />
              <i class="fas fa-star" />
              <i class="fas fa-star" />
              <i class="fas fa-star" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- testimonial-area end -->
