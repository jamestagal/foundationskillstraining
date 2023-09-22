<script>
    export let title1, title2, subtitle, card1, card2, card3, card4, card5, card6;
</script>
<!-- feature area -->
<div class="feature-area py-120">
    <div class="container">
        <div class="row">
            <div class="col-lg-6 mx-auto">
                <div class="site-heading text-center">
                    <h2 class="site-title mb-2">{title1} <span>{title2}</span></h2>
                    <p>{subtitle}</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6 col-lg-4">
                <div class="feature-item">
                    <div class="feature-icon feature-icon-1">
                        <i class="far fa-book-open"></i>
                    </div>
                    <div class="feature-content">
                        <h4>{card1.title}</h4>
                        <p>{card1.body}.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6 col-lg-4">
                <div class="feature-item active">
                    <div class="feature-icon feature-icon-2">
                        <i class="far fa-users"></i>
                    </div>
                    <div class="feature-content">
                        <h4>{card2.title}</h4>
                        <p>{card2.body}</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6 col-lg-4">
                <div class="feature-item">
                    <div class="feature-icon feature-icon-3">
                        <i class="far fa-clock"></i>
                    </div>
                    <div class="feature-content">
                        <h4>{card3.title}</h4>
                        <p>{card3.body}</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6 col-lg-4">
                <div class="feature-item">
                    <div class="feature-icon feature-icon-1">
                        <i class="far fa-book-open"></i>
                    </div>
                    <div class="feature-content">
                        <h4>{card4.title}</h4>
                        <p>{card4.body}.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6 col-lg-4">
                <div class="feature-item active">
                    <div class="feature-icon feature-icon-2">
                        <i class="far fa-users"></i>
                    </div>
                    <div class="feature-content">
                        <h4>{card5.title}</h4>
                        <p>{card5.body}</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6 col-lg-4">
                <div class="feature-item">
                    <div class="feature-icon feature-icon-3">
                        <i class="far fa-clock"></i>
                    </div>
                    <div class="feature-content">
                        <h4>{card6.title}</h4>
                        <p>{card6.body}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- feature area end -->
