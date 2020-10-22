<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    {% include bootstrap-head.html %}
    <title>{{ page.title }}</title>
    
  </head>
  <body>
    <div class="container page-header">
      {% include nav.html %}
    </div>
    <h1>{{ page.title }}</h1>
    <div class="container page-content">
      {{ content }}
    </div>
    <div class="container page-footer">
    <footer>
      &copy; {{ "now" | date: "%Y" }} {{site.author}}
    </footer>
    </div>
    {% include bootstrap-tail.html %}
  </body>
</html>