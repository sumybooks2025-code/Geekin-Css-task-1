<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8
    
<!-- ===== Embedded CSS ===== -->
<style>
  /* ===== Global Styles ===== */
* {
  
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f5f5f5;
}

/* ===== Navbar ===== */
.navbar {
  display: flex;
  align-items: center;
  gap: 20px;
  background-color: #131921;
  padding: 15px;
  color: white;
}

.logo {
  font-size: 1.6rem;
}

.search-bar {
  flex: 1;
  padding: 10px;
  font-size: 1rem;
}

.cart-btn {
  padding: 10px 15px;
  background-color: #f0c14b;
  border: none;
  cursor: pointer;
}

/* ===== Hero ===== */
.hero {
  background-color: #232f3e;
  color: white;
  text-align: center;
  padding: 3rem;
}

/* ===== Product Grid ===== */
.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 30px;
}

/* ===== Product Card ===== */
.product-card {
  background-color: white;
  padding: 15px;
  border: 2px solid #ddd;
  border-radius: 6px;
  text-align: center;
}

.product-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  margin-bottom: 10px;
}

.product-card h3 {
  font-size: 1.1rem;
  margin-bottom: 5px;
}

.price {
  color: #b12704;
  font-weight: bold;
  margin-bottom: 10px;
}

.product-card button {
  width: 100%;
  padding: 10px;
  background-color: #f0c14b;
  border: none;
  cursor: pointer;
}

/* ===== Footer ===== */
.footer {
  background-color: #131921;
  color: white;
  text-align: center;
  padding: 20px;
}  
</style>
 </head>

 <body>
  
  <!-- ===== Top Navigation (Amazon/Temu style) ===== -->
  
  <header class="navbar">
    <h1 class="Logo" href="[Logo] (Logo.png)" Sumys Varieties</h1>
    <input type="text" placeholder="Search products..." 
  

  <!-- ===== Hero Section ===== -->
  <section class="hero">
    <h2>Welcome to Sumys Varieties Online Store</h2>
    <p>Affordable products • Quality guaranteed • Fast delivery</p>
  </section>

  <!-- ===== Product Grid ===== -->
  <main class="product-grid">

    <!-- Product 1 -->
    <div class="product-card">
      <img src="" alt="Product Image 1">[bodycream] <img src="bodycream.png>
      <h3>bodycream</h3>
      <p class="price">₦7,000</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 2 -->
    <div class="product-card">
      <img src="" alt="Product Image 2">
      <h3>liquid soap</h3>
      <p class="price">₦8,500</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 3 -->
    <div class="product-card">
      <img src=".liquid soap" alt="Atamfa 3">
      <h3>Atamfa</h3>
      <p class="price">₦12,000</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 4 -->
    <div class="product-card">
      <img src="" alt="Product Image 4">
      <h3>babies gown</h3>
      <p class="price">₦7,000</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 5 -->
    <div class="product-card">
      <img src="" alt="Product Image 5">
      <h3>Babies Gown</h3>
      <p class="price">₦15,000</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 6 -->
    <div class="product-card">
      <img src="" alt="Product Image 6">
      <h3>Boys trouser</h3>
      <p class="price">₦9,500</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 7 -->
    <div class="product-card">
      <img src="" alt="Product Image 7">
      <h3>Lace </h3>
      <p class="price">₦6,000</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 8 -->
    <div class="product-card">
      <img src="" alt="Product Image 8">
      <h3>Detergents</h3>
      <p class="price">₦11,000</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 9 -->
    <div class="product-card">
      <img src="" alt="Product Image 9">
      <h3>Box Bags</h3>
      <p class="price">₦13,500</p>
      <button>Add to Cart</button>
    </div>

    <!-- Product 10 -->
    <div class="product-card">
      <img src="" alt="Product Image 10">
      <h3>Mix and Match</h3>
      <p class="price">₦5,500</p>
      <button>Add to Cart</button>
    </div>

  </main>

  <!-- ===== Footer ===== -->
  <footer class="footer">
    <p>© 2026 Sumys Varieties Online Store. All rights reserved.</p>
  </footer>

</body>
</html>
  
