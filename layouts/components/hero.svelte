<script>
    export let subtitle, title1, title2, body, heroShape1, heroShape2, heroShape3, heroShape4, bgImage, search;
</script>
<!-- hero area -->
<div class="hero-section">
    <div class="hero-single">
        <div class="hero-shape-area">
            <img class="hero-shape-1" src="{heroShape1.src}" alt="{heroShape1.alt}">
            <img class="hero-shape-2" src="{heroShape2.src}" alt="{heroShape2.alt}">
            <img class="hero-shape-3" src="{heroShape3.src}" alt="{heroShape3.alt}">
            <img class="hero-shape-4" src="{heroShape4.src}" alt="{heroShape4.alt}">
        </div>
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-8 col-lg-6">
                    <div class="hero-content">
                        <h6 class="hero-sub-title wow animate__animated animate__fadeInUp"
                            data-wow-duration="1s" data-wow-delay=".25s">{subtitle}</h6>
                        <h1 class="hero-title wow animate__animated animate__fadeInUp" data-wow-duration="1s"
                            data-wow-delay=".50s">
                            {title1} <span> {title2}</span>
                        </h1>
                        <p class="wow animate__animated animate__fadeInUp" data-wow-duration="1s"
                            data-wow-delay=".75s">
                            {body}
                        </p>
                        <div class="hero-search">
                            <form action="#">
                                <div class="form-group">
                                    <i class="far fa-search"></i>
                                    <input type="text" class="form-control"
                                        placeholder="Search Your Course Today...">
                                    <button type="submit">{search.button}</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-6">
                    <div class="hero-img" style="background-image: url({bgImage.src})" alt="{bgImage.alt}"></div>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- hero area end -->