<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    {% include bootstrap-head.html %}
    <title>{{ page.title }}</title>
    
  </head>
  <body>
    <div class="container site-header">
      {% include nav.html %}
    </div>
    <div class="container page-header">
      <h1>{{ page.title }}</h1>
    </div>
    <div class="container page-content">
      {{ content }}
    </div>
    <div class="container page-footer">
    <div class="my-auto">
        <footer>
          &copy; {{ "now" | date: "%Y" }} {{site.author}}
        </footer>
      </div>
    </div>
    {% include bootstrap-tail.html %}
  </body>
</html>