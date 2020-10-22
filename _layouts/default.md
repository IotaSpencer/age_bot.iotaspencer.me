<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    {% include bootstrap-head.html %}
    <title>{{ page.title }}</title>
    
  </head>
  <body class="bg-dark">
    <div class="container site-header bg-dark">
      {% include nav.html %}
    </div>
    <div class="container page-header bg-dark">
      <h1>{{ page.title }}</h1>
    </div>
    <div class="container page-content bg-dark">
      {{ content }}
    </div>
    <div class="container page-footer bg-dark">
    <div class="my-auto mx-auto bg-dark">
        <footer>
          &copy; {{ "now" | date: "%Y" }} {{site.author}}
        </footer>
      </div>
    </div>
    {% include bootstrap-tail.html %}
  </body>
</html>