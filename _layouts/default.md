<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    {% include bootstrap-head.html %}
    <title>{{ page.title }}</title>
    
  </head>
  <body>
    {% include nav.html %}
    <h1>{{ page.title }}</h1>
    <div class="page-content">
      {{ content }}
    </div>
    <footer>
      &copy; {{ "now" | date: "%Y" }} {{site.author}}
    </footer>
    {% include bootstrap-tail.html %}
  </body>
</html>