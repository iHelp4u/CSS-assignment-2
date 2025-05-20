# CSS-assignment-2
CSS assignment 2
@@ -0,0 +1,67 @@
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" type="text/css" href="style.css" />
    <title>Document</title>
  </head>
  <body>
    <header>
      <img src="Unknown.png" alt="Google" />
    </header>
    <main class="main-block">
      <section>
        <form class="search-form">
          <label for="search"> Search the web using Google! </label>
          <input type="text" id="search" name="query"  class="search-input" />
          <div>
            <button>Google Search</button>
            <button>I'm feeling lucky</button>
          </div>
        </form>
      </section>
      <section class="boxes-section">
        <div class="box margin-box">
          <ul>
            <li><a href="">Special Searches</a></li>
            <li><a href="">Stanford Search</a></li>
            <li><a href="">Linux Search</a></li>
          </ul>
        </div>
        <div class="box margin-box">
          <ul>
            <li><a href="">Help!</a></li>
            <li><a href="">About Google!</a></li>
            <li><a href="">Company Info</a></li>
            <li><a href="">Google! Logos</a></li>
          </ul>
        </div>
        <div class="box">
          <form class="subscribe-form">
            <label for="email">
              Get Google! <br />
              updates monthly:</label
            >
            <input
              type="text"
              id="email"
              name="email"
              placeholder="your e-mail"
            />
            <div>
              <button>Subscribe</button>
              <a href="">Archive</a>
            </div>
          </form>
        </div>
      </section>
    </main>
    <footer>
      <p>Copvright @1998 Google Inc.</p>
    </footer>
  </body>
</html>
