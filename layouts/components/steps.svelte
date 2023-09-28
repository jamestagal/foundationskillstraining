<script>
  export let title1, description, step1, step2, step3;
</script>

<!-- step area -->
<div class="step-area">
  <div class="container">
    <div class="row">
      <div class="col-lg-6">
        <div class="step-content">
          <div class="site-heading">
            <h2 class="site-title mb-10">
              <br /><span>{title1}</span>
            </h2>
            <p>
              {description}
            </p>
          </div>
          <div class="step-content-wrapper">
            <div class="step-item">
              <div class="step-count">
                <span>{step1.number}</span>
              </div>
              <div class="step-item-info">
                <h3>{step1.title}</h3>
                <p>
                  {step1.description}
                </p>
              </div>
            </div>
            <div class="step-item">
              <div class="step-count">
                <span>{step2.number}</span>
              </div>
              <div class="step-item-info">
                <h3>{step2.title}</h3>
                <p>
                  {step2.description}
                </p>
              </div>
            </div>
            <div class="step-item">
              <div class="step-count">
                <span>{step3.number}</span>
              </div>
              <div class="step-item-info">
                <h3>{step3.title}</h3>
                <p>
                  {step3.description}
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="step-img">
          <div class="video-wrapper">
            <a
              class="play-btn popup-youtube"
              href="https://www.youtube.com/watch?v=ckHzmP1evNU"
            >
              <i class="fas fa-play" />
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- step area end -->
