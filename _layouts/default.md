<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>{{ page.title }}</title>
  <meta name="description" content="{{ page.description }}">
  <link rel="stylesheet" type="text/css" href="/css/flowbite.min.css" />
  <link rel="icon" href="favicon.png">
  <!-- Add other meta tags as needed -->
  <meta property="og:title" content="{{ page.og_title }}">
  <meta property="og:description" content="{{ page.og_description }}">
  <meta property="og:image" content="{{ page.og_image | absolute_url }}">
  <!-- Add other OG tags as needed -->
</head>
<body>
  <header>
    <!-- Navigation menu goes here -->
    {% include navigation.md %}
  </header>
  <main>
    {{ content }}
  </main>
  <footer>
    <!-- Footer content goes here -->
  </footer>
</body>
</html>
