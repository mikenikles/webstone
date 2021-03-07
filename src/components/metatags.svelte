<script>
  const title = "The cornerstone of your next web app | Webstone";
  const description = "Webstone guides you through the setup of your next wep app. Pick & choose your CSS framework, linting, formatting, even your preferred hosting provider.";
  const websiteDomain = "webstone.app";
  const websiteUrl = `https://${websiteDomain}`;
  const imageUrl = `${websiteUrl}/social-media-preview.png`;
</script>

<svelte:head>
  <!-- HTML Meta Tags -->
  <title>{title}</title>
  <meta name="description" content="{description}">

  <!-- Facebook Meta Tags -->
  <meta property="og:url" content="{websiteUrl}">
  <meta property="og:type" content="website">
  <meta property="og:title" content="{title}">
  <meta property="og:description" content="{description}">
  <meta property="og:image" content="{imageUrl}">

  <!-- Twitter Meta Tags -->
  <meta name="twitter:card" content="summary_large_image">
  <meta property="twitter:domain" content="{websiteDomain}">
  <meta property="twitter:url" content="{websiteUrl}">
  <meta name="twitter:title" content="{title}">
  <meta name="twitter:description" content="{description}">
  <meta name="twitter:image" content="{imageUrl}">

  <!-- Meta Tags Generated via https://www.opengraph.xyz -->
</svelte:head>