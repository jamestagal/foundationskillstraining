<script>
  export let title, env;
</script>

<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />

  <title
    >{title
      ? title + " | Foundation Skills Training"
      : "Foundation Skills Training"}</title
  >
  <base href={env.baseurl} />
  <script type="module" src="/spa/core/main.js"></script>
  <link
    href="https://fonts.googleapis.com/css2?family=Heebo:wght@300;400;500;600;700;800;900&family=Roboto:wght@100;300;400;500;700;900&display=swap"
    rel="stylesheet"
  />
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
    crossorigin="anonymous"
  />
  <link rel="icon" type="image/svg+xml" href="media/logo/favicon.png" />
  <link rel="stylesheet" href="spa/bundle.css" />
  <link rel="stylesheet" href="global.css" />
  <link rel="stylesheet" href="all-fontawesome.min.css" />
  <link rel="stylesheet" href="bootstrap.min.css" />
</head>
