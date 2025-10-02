#Ex.07 Restaurant Website
#Date: 01-10-2025
#AIM:
#To develop a static Restaurant website to display the food items and services provided by them.

#DESIGN STEPS:
#Step 1:
#Requirement collection.

#Step 2:
#Creating the layout using HTML and CSS.

#Step 3:
#Updating the sample content.

#Step 4:
#Choose the appropriate style and color scheme.

#Step 5:
#Validate the layout in various browsers.

#Step 6:
#Validate the HTML code.

#Step 7:
#Publish the website in the given URL.

#PROGRAM:

```

<!-- ========================= index.html ========================= -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>La Rustica - Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-flex">
      <div class="logo">
        <img src="logo.jpg" alt="Restaurant Logo" class = "The Golden Spoon">
        <span class="site-name">
          <b>The Golden Spoon
            </b>
          </span>
      </div>

      <nav>
        <ul class="nav">
          <li><a href="index.html" class="active">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="admin.html">Administration</a></li>
          <li><a href="contact.html">Contact Us</a></li>
        </ul>
      </nav>
    </div>
    <div class="banner">
      <img src="hostes.jpg" alt="Restaurant Banner">
      <div class="The Golden Spoon">
        <style>
          h2 {text-align: center;}
        </style>

        <h2>Authentic Flavours • Fresh Ingredients • Warm Hospitality</h2>
        <style>
          p {text-align: center;}
        </style>
        <p>Family recipes, modern plating — welcome to La Rustica.</p>
      </div>
    </div>
  </header>

  <main class="container main-home">
    <section class="intro">
      <h2>About Us</h2>
      <p>
        La Rustica brings the rustic warmth of traditional kitchens to your table. We believe in seasonal produce, handmade sauces,
        and friendly service. Join us for breakfast, lunch or a relaxed dinner.
      </p>
    </section>

    <section class="highlights">
      <div class="card">
        <style>
          p {text-align: center;}
          h3 {text-align: center;}
        </style>
        <h3>Fresh Ingredients</h3>
        <p>Locally sourced vegetables, meats and artisanal breads baked daily.</p>
      </div>
      <div class="card">
        <style>
          p {text-align: center;}
          h3 {text-align: center;}
        </style>
        <h3>Chef's Specials</h3>
        <p>Rotating weekly menus inspired by regional and international cuisine.</p>
      </div>
      <div class="card">
        <style>
          p {text-align: center;}
          h3 {text-align: center;}
        </style>
        <h3>Cozy Ambience</h3>
        <p>Comfortable seating, soft lighting — perfect for family & friends.</p>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-grid">
      <div>
        <h4>La Rustica</h4>
        <p>123 Spice Street, Foodville</p>
      </div>
      <div>
        <h4>Quick Links</h4>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="admin.html">Administration</a></li>
        </ul>
      </div>
      <div>
        <h4>Contact</h4>
        <p>Phone: +91-98765-43210</p>
        <p>Email: contact@larustica.example</p>
      </div>
    </div>
    <div class="footer-bottom">Designed by Rishwanth S V</div>
  </footer>
</body>
</html>


<!-- ========================= menu.html ========================= -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>La Rustica - Menu</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header small">
    <div class="container header-flex">
      <h1 class="logo">La Rustica</h1>
      <nav>
        <ul class="nav">
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html" class="active">Menu</a></li>
          <li><a href="admin.html">Administration</a></li>
          <li><a href="contact.html">Contact Us</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <h2 class="page-title">Our Menu</h2>
    <p class="lead">Explore our curated selection — 12 delicious items below.</p>

    <section class="menu-grid">
      <!-- 12 food items -->
      <article class="menu-item">
        <img src="salad.jpeg" alt="Caesar Salad">
        <h3>Caesar Salad</h3>
        <p>Crisp romaine, parmesan, anchovy dressing.</p>
        <span class="price">₹149</span>
      </article>

      <article class="menu-item">
        <img src="vella.jpeg" alt="Vella Paniyaram">
        <h3>Vella Paniyaram</h3>
        <p>White rice and dal fritters.</p>
        <span class="price">₹299</span>
      </article>

      <article class="menu-item">
        <img src="arisi.jpeg" alt="Arisi Paruppu Sadam">
        <h3>Arisi Paruppu Sadam</h3>
        <p>Kongu rice and lentil dish.</p>
        <span class="price">₹199</span>
      </article>

      <article class="menu-item">
        <img src="chicken.jpeg" alt="Chicken Chettinad">
        <h3>Chicken Chettinad</h3>
        <p>fiery chicken curry</p>
        <span class="price">₹249</span>
      </article>

      <article class="menu-item">
        <img src="muttonchuk.jpeg" alt="Mutton Chukka Varuval">
        <h3>Mutton CHukka Varuval</h3>
        <p>Spicy dry roasted mutton.</p>
        <span class="price">₹329</span>
      </article>

      <article class="menu-item">
        <img src="mush.jpeg" alt="Mushroom Risotto">
        <h3>Mushroom Risotto</h3>
        <p>Creamy arborio rice with wild mushrooms.</p>
        <span class="price">₹279</span>
      </article>

      <article class="menu-item">
        <img src="salmon.jpeg" alt="Grilled Salmon">
        <h3>Grilled Salmon</h3>
        <p>Herb butter, seasonal vegetables.</p>
        <span class="price">₹399</span>
      </article>

      <article class="menu-item">
        <img src="chick.jpeg" alt="Tandoori Chicken">
        <h3>Tandoori Chicken</h3>
        <p>Spiced and char-grilled, served with mint chutney.</p>
        <span class="price">₹289</span>
      </article>

      <article class="menu-item">
        <img src="chicktikk.jpeg" alt="Chicken Tikka Masala">
        <h3>Chicken Tikka Masala</h3>
        <p>Creamy, spiced chicken curry.</p>
        <span class="price">₹219</span>
      </article>

      <article class="menu-item">
        <img src="ice.jpeg" alt="Gelato Scoop">
        <h3>Gelato Scoop</h3>
        <p>Choose from vanilla, chocolate, pistachio.</p>
        <span class="price">₹99</span>
      </article>

      <article class="menu-item">
        <img src="burger.jpeg" alt="Gourmet Burger">
        <h3>Gourmet Burger</h3>
        <p>Beef patty, cheddar, caramelised onions, fries.</p>
        <span class="price">₹259</span>
      </article>

      <article class="menu-item">
        <img src="margheritta.jpeg" alt="Margherita Pizza">
        <h3>Margherita Pizza</h3>
        <p>Fresh basil, tomato, mozzarella.</p>
        <span class="price">₹129</span>
      </article>

    </section>
  </main>

  <footer class="site-footer small">
    <div class="container footer-grid">
      <div>
        <h4>La Rustica</h4>
        <p>123 Spice Street, Foodville</p>
      </div>
      <div class="footer-bottom">Designed by Rishwanth S V</div>
    </div>
  </footer>
</body>
</html>


<!-- ========================= admin.html ========================= -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>La Rustica - Administration</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header small">
    <div class="container header-flex">
      <h1 class="logo">La Rustica</h1>
      <nav>
        <ul class="nav">
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="admin.html" class="active">Administration</a></li>
          <li><a href="contact.html">Contact Us</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <h2 class="page-title">Administration</h2>
    <p class="lead">Meet our team</p>

    <section class="team-grid">
      <!-- Six people with photos and designations -->
      <article class="team-member">
        <img src="head.jpeg" alt="Head Chef">
        <h3>Chef Arjun Rao</h3>
        <p>Head Chef</p>
      </article>

      <article class="team-member">
        <img src="manager.jpeg" alt="Restaurant Manager">
        <h3>Priya Menon</h3>
        <p>Restaurant Manager</p>
      </article>

      <article class="team-member">
        <img src="souschef.jpeg" alt="Sous Chef">
        <h3>Ramesh Kumar</h3>
        <p>Sous Chef</p>
      </article>

      <article class="team-member">
        <img src="host.jpeg" alt="Host">
        <h3>Anika Das</h3>
        <p>Host</p>
      </article>

      <article class="team-member">
        <img src="sommelier.jpeg" alt="Sommelier">
        <h3>Karan Verma</h3>
        <p>Sommelier</p>
      </article>

      <article class="team-member">
        <img src="accountant.jpeg" alt="Accountant">
        <h3>Meera Iyer</h3>
        <p>Accounts & Admin</p>
      </article>
    </section>
  </main>

  <footer class="site-footer small">
    <div class="container footer-grid">
      <div>
        <h4>La Rustica</h4>
        <p>123 Spice Street, Foodville</p>
      </div>
      <div class="footer-bottom">Designed by Rishwanth S V</div>
    </div>
  </footer>
</body>
</html>


<!-- ========================= contact.html ========================= -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>La Rustica - Contact Us</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header small">
    <div class="container header-flex">
      <h1 class="logo">La Rustica</h1>
      <nav>
        <ul class="nav">
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="admin.html">Administration</a></li>
          <li><a href="contact.html" class="active">Contact Us</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container contact-page">
    <h2 class="page-title">Contact Us</h2>
    <p class="lead">We'd love to hear from you. Reach out by phone, email or visit us.</p>

    <section class="contact-grid">
      <div class="contact-card">
        <h3>Address</h3>
        <p>La Rustica, 123 Spice Street,<br> Foodville, 600001</p>
      </div>

      <div class="contact-card">
        <h3>Phone</h3>
        <p>+91-98765-43210</p>
      </div>

      <div class="contact-card">
        <h3>Email</h3>
        <p>contact@larustica.example</p>
      </div>
    </section>

    <section class="contact-form">
      <h3>Send a Message</h3>
      <form>
        <label for="name">Name</label>
        <input id="name" type="text" placeholder="Your name">

        <label for="email">Email</label>
        <input id="email" type="email" placeholder="you@example.com">

        <label for="message">Message</label>
        <textarea id="message" rows="5" placeholder="Write your message..."></textarea>

        <button type="submit"> Submit </button>
      </form>
    </section>
  </main>

  <footer class="site-footer small">
    <div class="container footer-grid">
      <div>
        <h4>La Rustica</h4>
        <p>123 Spice Street, Foodville</p>
      </div>
      <div class="footer-bottom">Designed by Rishwanth S V</div>
    </div>
  </footer>
</body>
</html>

```

OUTPUT:


RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
