# ShopSmartNow
An affiliate marketing landing page built to showcase and promote selected Amazon items
git add .
git commit -m "Initial commit"
git push origin main
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Storefront</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f4f4e9;
      color: #000;
    }

    header {
      background: #fff;
      padding: 1rem 2rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 1px solid #ccc;
    }

    .logo {
      font-size: 2rem;
      font-family: 'Georgia', serif;
      letter-spacing: 2px;
    }

    nav {
      display: flex;
      gap: 1.5rem;
    }

    nav a {
      text-decoration: none;
      color: black;
      font-weight: bold;
    }

    .search-bar {
      display: flex;
      margin: 2rem auto;
      justify-content: center;
    }

    .search-bar input {
      width: 300px;
      padding: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .recent-links {
      text-align: center;
      padding: 2rem;
    }

    .recent-links h2 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
    }

    .link-buttons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .link-buttons a {
      text-decoration: none;
      padding: 1rem 2rem;
      border: 1px solid #000;
      background: #fff;
      color: #000;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    .link-buttons a:hover {
      background: #000;
      color: #fff;
    }

    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #333;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }

      .search-bar input {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">YOUR BRAND</div>
    <nav>
      <a href="#">Today's Deals</a>
      <a href="#">Categories</a>
      <a href="#">Unique Finds</a>
      <a href="#">Blog</a>
      <a href="#">Account</a>
    </nav>
  </header>

  <div class="search-bar">
    <input type="text" placeholder="Search products..." />
  </div>

  <section class="recent-links">
    <h2>RECENT LINKS</h2>
    <div class="link-buttons">
      <a href="https://www.amazon.com/yourstorefront" target="_blank">Amazon Storefront</a>
      <a href="https://www.amazon.com/gp/goldbox" target="_blank">Today's Deals</a>
      <a href="https://www.shopltk.com/explore/yourname" target="_blank">LTK Shop</a>
    </div>
  </section>

  <footer>
    As an Amazon Affiliate I may earn from qualifying purchases.
  </footer>

</body>
</html>
