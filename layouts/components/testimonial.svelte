<script>
  export let title1, title2, title3, subtitle, card1, card2;
</script>

<!-- testimonial-area -->
<div class="testimonial-area bg py-120">
  <div class="container">
    <div class="row">
      <div class="col-lg-6 mx-auto">
        <div class="site-heading text-center">
          <h2 class="site-title">{title1} <span>{title2}</span> {title3}</h2>
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
            {card1.quote}
          </p>
        </div>
        <div class="testimonial-content">
          <div class="testimonial-author-img">
            <img src={card1.src} alt={card1.altText} />
          </div>
          <div class="testimonial-author-info">
            <h4>{card1.name}</h4>
            <p>{card1.title}</p>
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
            {card2.quote}
          </p>
        </div>
        <div class="testimonial-content">
          <div class="testimonial-author-img">
            <img src={card2.src} alt={card2.altText} />
          </div>
          <div class="testimonial-author-info">
            <h4>{card2.name}</h4>
            <p>{card2.title}</p>
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
