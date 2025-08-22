<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SimpleFoodSite – Delicious Recipes</title>
<style>
/* General */
* { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
body { background-color: #fff8f0; color: #333; line-height: 1.6; }
/* Header */
.header { background: #ff7f50; color: white; padding: 15px 0; }
.header .container { width: 90%; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; }
.header nav a { color: white; margin-left: 20px; text-decoration: none; font-weight: bold; }
/* Hero */
.hero { position: relative; text-align: center; margin-bottom: 40px; }
.hero img { width: 100%; max-height: 400px; object-fit: cover; }
.hero-text { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); background: rgba(0,0,0,0.4); color: white; padding: 20px; border-radius: 8px; }
/* Cards */
.cards { display: flex; gap: 20px; flex-wrap: wrap; justify-content: center; margin-bottom: 40px; }
.card { background: white; border-radius: 8px; overflow: hidden; width: 250px; box-shadow: 0 2px 6px rgba(0,0,0,0.2); text-align: center; }
.card img { width: 100%; height: 150px; object-fit: cover; }
.card h4 { padding: 10px 0; }
.card a { display: inline-block; margin-bottom: 10px; padding: 5px 10px; background-color: #ff7f50; color: white; text-decoration: none; border-radius: 4px; }
/* Sections */
.container { width: 90%; margin: 0 auto; }
section { margin-bottom: 40px; }
h3 { text-align: center; margin-bottom: 20px; }
/* Recipe Page Section */
.recipe-page img { width: 100%; max-width: 600px; display: block; margin: 20px auto; border-radius: 8px; }
.recipe-page ul, .recipe-page ol { width: 90%; max-width: 600px; margin: 0 auto 20px auto; }
/* Newsletter */
.newsletter { text-align: center; padding: 20px; background: #ffe0cc; border-radius: 8px; width: 80%; margin: 0 auto 40px auto; }
.newsletter input[type="email"] { padding: 8px; width: 60%; max-width: 300px; margin-right: 10px; border-radius: 4px; border: 1px solid #ccc; }
.newsletter button { padding: 8px 15px; background: #ff7f50; color: white; border: none; border-radius: 4px; cursor: pointer; }
.newsletter p { margin-top: 10px; color: green; font-weight: bold; }
/* Footer */
footer { background: #333; color: white; text-align: center; padding: 15px 0; }
</style>
</head>
<body>

<!-- Header -->
<header class="header">
  <div class="container">
    <h1 class="logo">SimpleFoodSite</h1>
    <nav>
      <a href="#hero">Home</a>
      <a href="#recipes">Recipes</a>
      <a href="#shop">Shop</a>
      <a href="#newsletter">Subscribe</a>
    </nav>
  </div>
</header>

<!-- Hero -->
<section id="hero" class="hero">
  <img src="https://via.placeholder.com/1200x400.png?text=Delicious+Recipes" alt="Food Banner">
  <div class="hero-text">
    <h2>Quick & Tasty Recipes</h2>
    <p>Discover simple recipes and useful kitchen tools!</p>
  </div>
</section>

<!-- Featured Recipes -->
<section id="recipes" class="recipes container">
  <h3>Featured Recipes</h3>
  <div class="cards">
    <div class="card">
      <img src="https://via.placeholder.com/250x150.png?text=Chicken+Curry" alt="Chicken Curry">
      <h4>Chicken Curry</h4>
      <a href="#recipe1">View Recipe</a>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/250x150.png?text=Veg+Biryani" alt="Veg Biryani">
      <h4>Veg Biryani</h4>
      <a href="#recipe2">View Recipe</a>
    </div>
  </div>
</section>

<!-- Sample Recipe Section -->
<section class="recipe-page container" id="recipe1">
  <h3>Easy Chicken Curry</h3>
  <img src="https://via.placeholder.com/600x400.png?text=Chicken+Curry" alt="Chicken Curry">
  <h4>Ingredients:</h4>
  <ul>
    <li>500g chicken</li>
    <li>2 onions</li>
    <li>3 tomatoes</li>
    <li>Spices as needed</li>
  </ul>
  <h4>Instructions:</h4>
  <ol>
    <li>Fry onions until golden brown.</li>
    <li>Add chicken and spices, cook 10 minutes.</li>
    <li>Add tomatoes and simmer until cooked.</li>
    <li>Serve hot with rice or bread.</li>
  </ol>
</section>

<section class="recipe-page container" id="recipe2">
  <h3>Quick Veg Biryani</h3>
  <img src="https://via.placeholder.com/600x400.png?text=Veg+Biryani" alt="Veg Biryani">
  <h4>Ingredients:</h4>
  <ul>
    <li>2 cups basmati rice</li>
    <li>Mixed vegetables</li>
    <li>Onions & tomatoes</li>
    <li>Spices as needed</li>
  </ul>
  <h4>Instructions:</h4>
  <ol>
    <li>Cook rice and keep aside.</li>
    <li>Fry vegetables with onions and spices.</li>
    <li>Mix rice with vegetables and simmer 5 minutes.</li>
    <li>Serve hot with raita.</li>
  </ol>
</section>

<!-- Shop Section -->
<section id="shop" class="container">
  <h3>Recommended Kitchen Tools</h3>
  <div class="cards">
    <div class="card">
      <img src="https://via.placeholder.com/250x150.png?text=Blender" alt="Blender">
      <h4>High-Speed Blender</h4>
      <a href="#">Buy Now</a>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/250x150.png?text=Knife+Set" alt="Knife Set">
      <h4>Professional Knife Set</h4>
      <a href="#">Buy Now</a>
    </div>
  </div>
</section>

<!-- Newsletter -->
<section id="newsletter" class="newsletter">
  <h3>Subscribe for Weekly Recipes</h3>
  <form id="newsletterForm">
    <input type="email" placeholder="Enter your email" required>
    <button type="submit">Subscribe</button>
  </form>
  <p id="successMsg"></p>
</section>

<!-- Footer -->
<footer>
  <p>&copy; 2025 SimpleFoodSite. All rights reserved.</p>
</footer>

<script>
// Newsletter form submission
document.getElementById("newsletterForm").addEventListener("submit", function(e){
  e.preventDefault();
  document.getElementById("successMsg").textContent = "Thank you for subscribing!";
  this.reset();
});
</script>

</body>
</html>
