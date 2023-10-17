<script>
  export let title1, title2, subtitle, student1, student2;
</script>

<div class="testimonial-area bg py-120 inherited-styles-for-exported-element">
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
    <div class="testimonial-slider owl-carousel owl-theme owl-loaded owl-drag">
      <div class="owl-stage-outer">
        <div
          class="owl-stage"
          style="transform: translate3d(-1786px, 0px, 0px); transition: all 0.25s ease 0s; width: 4764px;"
        >
          <div
            class="owl-item active"
            style="width: 565.5px; margin-right: 30px;"
          >
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
          </div>
          <div
            class="owl-item active"
            style="width: 565.5px; margin-right: 30px;"
          >
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
          <div class="owl-item" style="width: 565.5px; margin-right: 30px;">
            <div class="testimonial-single">
              <div class="testimonial-quote">
                <span class="testimonial-quote-icon"
                  ><i class="fal fa-quote-right" /></span
                >
                <p>
                  "There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomised words which don't look
                  even slightly believable. If you are going to use a passage."
                </p>
              </div>
              <div class="testimonial-content">
                <div class="testimonial-author-img">
                  <img
                    src="https://live.themewild.com/eduhub/assets/img/testimonial/01.png"
                    alt=""
                  />
                </div>
                <div class="testimonial-author-info">
                  <h4>Sylvia H Green</h4>
                  <p>Student</p>
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
          <div
            class="owl-item cloned"
            style="width: 565.5px; margin-right: 30px;"
          >
            <div class="testimonial-single">
              <div class="testimonial-quote">
                <span class="testimonial-quote-icon"
                  ><i class="fal fa-quote-right" /></span
                >
                <p>
                  "There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomised words which don't look
                  even slightly believable. If you are going to use a passage."
                </p>
              </div>
              <div class="testimonial-content">
                <div class="testimonial-author-img">
                  <img
                    src="https://live.themewild.com/eduhub/assets/img/testimonial/02.png"
                    alt=""
                  />
                </div>
                <div class="testimonial-author-info">
                  <h4>Gordon D Novak</h4>
                  <p>Student</p>
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
          <div
            class="owl-item cloned"
            style="width: 565.5px; margin-right: 30px;"
          >
            <div class="testimonial-single">
              <div class="testimonial-quote">
                <span class="testimonial-quote-icon"
                  ><i class="fal fa-quote-right" /></span
                >
                <p>
                  "There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomised words which don't look
                  even slightly believable. If you are going to use a passage."
                </p>
              </div>
              <div class="testimonial-content">
                <div class="testimonial-author-img">
                  <img
                    src="https://live.themewild.com/eduhub/assets/img/testimonial/03.png"
                    alt=""
                  />
                </div>
                <div class="testimonial-author-info">
                  <h4>Reid E Butt</h4>
                  <p>Student</p>
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
          <div class="owl-item" style="width: 565.5px; margin-right: 30px;">
            <div class="testimonial-single">
              <div class="testimonial-quote">
                <span class="testimonial-quote-icon"
                  ><i class="fal fa-quote-right" /></span
                >
                <p>
                  "There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomised words which don't look
                  even slightly believable. If you are going to use a passage."
                </p>
              </div>
              <div class="testimonial-content">
                <div class="testimonial-author-img">
                  <img
                    src="https://live.themewild.com/eduhub/assets/img/testimonial/04.png"
                    alt=""
                  />
                </div>
                <div class="testimonial-author-info">
                  <h4>Parker Jimenez</h4>
                  <p>Student</p>
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
          <div
            class="owl-item cloned"
            style="width: 565.5px; margin-right: 30px;"
          >
            <div class="testimonial-single">
              <div class="testimonial-quote">
                <span class="testimonial-quote-icon"
                  ><i class="fal fa-quote-right" /></span
                >
                <p>
                  "There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomised words which don't look
                  even slightly believable. If you are going to use a passage."
                </p>
              </div>
              <div class="testimonial-content">
                <div class="testimonial-author-img">
                  <img
                    src="https://live.themewild.com/eduhub/assets/img/testimonial/01.png"
                    alt=""
                  />
                </div>
                <div class="testimonial-author-info">
                  <h4>Sylvia H Green</h4>
                  <p>Student</p>
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
          <div
            class="owl-item cloned"
            style="width: 565.5px; margin-right: 30px;"
          >
            <div class="testimonial-single">
              <div class="testimonial-quote">
                <span class="testimonial-quote-icon"
                  ><i class="fal fa-quote-right" /></span
                >
                <p>
                  "There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration in some
                  form, by injected humour, or randomised words which don't look
                  even slightly believable. If you are going to use a passage."
                </p>
              </div>
              <div class="testimonial-content">
                <div class="testimonial-author-img">
                  <img
                    src="https://live.themewild.com/eduhub/assets/img/testimonial/02.png"
                    alt=""
                  />
                </div>
                <div class="testimonial-author-info">
                  <h4>Gordon D Novak</h4>
                  <p>Student</p>
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
      <div class="owl-nav disabled">
        <button type="button" role="presentation" class="owl-prev"
          ><i class="icofont-long-arrow-left" /></button
        ><button type="button" role="presentation" class="owl-next"
          ><i class="icofont-long-arrow-right" /></button
        >
      </div>
      <div class="owl-dots">
        <button role="button" class="owl-dot active"><span /></button><button
          role="button"
          class="owl-dot"><span /></button
        >
      </div>
    </div>
  </div>
</div>

<style>
  .inherited-styles-for-exported-element {
    color: #757f95;
    font-family: Roboto, sans-serif;
    font-size: 16px;
    font-weight: 400;
    line-height: 1.8;
    text-align: start;
  }

  img {
    height: auto;
    max-width: 100%;
    transition: all 0.3s ease-out;
    transition-behavior: normal;
    vertical-align: middle;
  }

  button {
    border-radius: 0;
    text-transform: none;
  }

  *,
  ::after,
  ::before {
    box-sizing: inherit;
  }

  h2,
  h4 {
    font-family: Heebo, sans-serif;
    line-height: 1.2;
  }

  h4 {
    color: #333;
    font-weight: 600;
  }

  h2 {
    margin-left: 0;
    margin-right: 0;
  }

  button,
  h4,
  p {
    margin: 0;
  }

  ::selection {
    background-color: #555;
    color: #fff;
    text-shadow: none;
  }

  ::placeholder {
    color: #999;
    font-size: 16px;
    opacity: 1;
  }

  [type="button"],
  button {
    appearance: button;
  }

  .container {
    margin-left: auto;
    margin-right: auto;
    padding-left: calc(1.5rem * 0.5);
    padding-right: calc(1.5rem * 0.5);
    width: 100%;
  }

  @media (min-width: 576px) {
    .container {
      max-width: 540px;
    }
  }

  @media (min-width: 768px) {
    .container {
      max-width: 720px;
    }
  }

  @media (min-width: 992px) {
    .container {
      max-width: 960px;
    }
  }

  @media (min-width: 1200px) {
    .container {
      max-width: 1140px;
    }
  }

  @media (min-width: 1400px) {
    .container {
      max-width: 1320px;
    }
  }

  .row {
    display: flex;
    flex-wrap: wrap;
    margin-left: calc(-0.5 * 1.5rem);
    margin-right: calc(-0.5 * 1.5rem);
    margin-top: calc(-1 * 0);
  }

  .row > * {
    flex-shrink: 0;
    margin-top: 0;
    max-width: 100%;
    padding-left: calc(1.5rem * 0.5);
    padding-right: calc(1.5rem * 0.5);
    width: 100%;
  }

  @media (min-width: 992px) {
    .col-lg-6 {
      flex: 0 0 auto;
      width: 50%;
    }
  }

  .fal,
  .fas {
    -webkit-font-smoothing: antialiased;
    display: inline-block;
    font-family: "Font Awesome 5 Pro";
    font-variant: normal;
    font-variant-position: normal;
    font-weight: 300;
    line-height: 1;
    text-rendering: auto;
  }

  .fas {
    font-weight: 900;
  }

  .owl-carousel {
    -webkit-tap-highlight-color: transparent;
    position: relative;
    width: 100%;
    z-index: 1;
  }

  .bg {
    background-color: #f7f8f9;
  }

  .site-heading {
    margin-bottom: 50px;
  }

  .site-title {
    color: #202029;
    font-size: 35px;
    font-weight: 700;
    margin-bottom: 0;
    margin-top: 5px;
    text-transform: capitalize;
  }

  .py-120 {
    padding: 120px 0;
  }

  @media (min-width: 1200px) {
    .container {
      max-width: 1185px;
    }
  }

  .testimonial-area {
    position: relative;
  }

  .testimonial-single {
    background-color: #fff;
    border-radius: 8px;
    padding: 30px;
  }

  .testimonial-content {
    align-items: center;
    column-gap: 15px;
    display: flex;
    justify-content: flex-start;
    margin-top: 20px;
    row-gap: 15px;
  }

  .testimonial-author-img {
    border-radius: 50%;
    width: 80px;
  }

  .testimonial-quote-icon {
    bottom: 10px;
    color: #00af92;
    font-size: 50px;
    position: absolute;
    right: 50px;
  }

  .testimonial-rate {
    color: #fd8e1f;
  }

  @media (max-width: 991px) {
    .testimonial-quote-icon {
      right: 20px;
    }
  }

  [type="button"]:not(:disabled),
  button:not(:disabled) {
    cursor: pointer;
  }

  .fa-quote-right::before {
    content: "";
  }

  .fa-star::before {
    content: "";
  }

  .site-title span {
    color: #00af92;
  }

  .site-heading p {
    font-size: 16px;
  }

  .testimonial-author-img img {
    border-radius: 50%;
  }

  .testimonial-author-info h4 {
    font-size: 20px;
  }

  .owl-carousel .owl-item {
    -webkit-tap-highlight-color: transparent;
    position: relative;
  }

  .owl-carousel .owl-stage {
    position: relative;
    touch-action: manipulation;
  }

  .owl-carousel .owl-stage-outer {
    overflow: hidden;
    position: relative;
    transform: translate3d(0, 0, 0);
  }

  .owl-carousel .owl-item {
    backface-visibility: hidden;
    float: left;
    min-height: 1px;
    transform: translate3d(0, 0, 0);
  }

  .owl-carousel.owl-loaded {
    display: block;
  }

  .owl-carousel .owl-dot {
    cursor: pointer;
    user-select: none;
  }

  .testimonial-area .owl-dots {
    margin-top: 50px;
    text-align: center;
  }

  button:focus:not(:focus-visible) {
    outline: 0;
  }

  .owl-carousel .owl-stage::after {
    clear: both;
    content: ".";
    display: block;
    height: 0;
    line-height: 0;
    visibility: hidden;
  }

  .owl-carousel .owl-item img {
    display: block;
    width: 100%;
  }

  .owl-carousel .owl-nav.disabled {
    display: none;
  }

  .owl-carousel .owl-nav .owl-next,
  .owl-carousel .owl-nav .owl-prev {
    cursor: pointer;
    user-select: none;
  }

  .owl-carousel.owl-drag .owl-item {
    touch-action: pan-y;
    user-select: none;
  }

  .owl-carousel .owl-nav button.owl-next,
  .owl-carousel .owl-nav button.owl-prev,
  .owl-carousel button.owl-dot {
    background-color: initial;
    background-position: 0 0;
    border-style: none;
    color: inherit;
    font-family: inherit;
    font-feature-settings: inherit;
    font-kerning: inherit;
    font-optical-sizing: inherit;
    font-size: inherit;
    font-stretch: inherit;
    font-style: inherit;
    font-variant: inherit;
    font-variant-position: inherit;
    font-variation-settings: inherit;
    font-weight: inherit;
    line-height: inherit;
    padding: 0 !important;
  }

  .testimonial-area .owl-dots .owl-dot span {
    background-color: #00af92;
    border-radius: 10px;
    display: inline-block;
    height: 7px;
    margin: 5px;
    transition: all 0.5s ease-in-out;
    transition-behavior: normal;
    width: 25px;
  }

  .testimonial-area .owl-dots .owl-dot.active span {
    background-color: #00af92;
    height: 7px;
    width: 7px;
  }

  * {
    scroll-behavior: inherit !important;
  }

  .mx-auto {
    margin-left: auto !important;
    margin-right: auto !important;
  }

  .text-center {
    text-align: center !important;
  }
</style>
