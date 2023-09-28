<script>
    export let title, home, image1, image2, image3, image4;
</script>
<div class="site-breadcrumb">
  <div class="hero-shape-area">
    <img class="hero-shape-1" src="{image1.url}" alt="{image1.alt}" />
    <img class="hero-shape-2" src="{image2.url}" alt="{image2.alt}" />
    <img class="hero-shape-3" src="{image3.url}" alt="{image3.alt}" />
    <img class="hero-shape-4" src="{image4.url}" alt="{image4.alt}" />
  </div>
  <div class="container">
    <h2 class="breadcrumb-title">{title}</h2>
    <ul class="breadcrumb-menu">
      <li><a href=".">{home}</a></li>
      <li class="active">{title}</li>
    </ul>
  </div>
</div>
