<template>
  <div class="home">
    <main>
      <!-- banner image -->
      <div class="banner">
        <div class="banner-text">
          <h1>My Blog</h1>
          <p>My blog is about...</p>
        </div>

        <div class="banner-image">
          <img src="../assets/cart.jpg" alt="banner image" />
        </div>
      </div>

      <div class="container-title">
        <h2>Products</h2>
      </div>

      <!-- product cards  -->
      <div class="container">
        <!-- Title -->
        <div class="card">
          <div class="card-image">
            <img src="../assets/cart.jpg" alt="product image" />
          </div>
          <div class="card-content">
            <h3>Product 1</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quae.</p>
          </div>
        </div>

        <div class="card">
          <div class="card-image">
            <img src="../assets/cart.jpg" alt="product image" />
          </div>
          <div class="card-content">
            <h3>Product 1</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quae.</p>
          </div>
        </div>

        <div class="card">
          <div class="card-image">
            <img src="../assets/cart.jpg" alt="product image" />
          </div>
          <div class="card-content">
            <h3>Product 1</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quae.</p>
          </div>
        </div>

        <div class="card">
          <div class="card-image">
            <img src="../assets/cart.jpg" alt="product image" />
          </div>
          <div class="card-content">
            <h3>Product 1</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quae.</p>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
</script>

<style>
.home {
  background-color: #f5f5f5;
}
.banner {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 2rem;
  background-color: #7f8c8d;
  height: 60vh;
}
.banner-text {
  width: 50%;
}
.banner-text h1 {
  color: #fff;
  font-size: 3rem;
}
.banner-text p {
  color: #fff;
  font-size: 1.5rem;
}
.banner-image {
  width: 50%;
  height: 100%;
  overflow: hidden;
}
.banner-image img {
  width: 100%;
}

.container-title {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 2rem;
  background-color: #ecf0f1;
}

.container-title h2 {
  color: #2c3e50;
}

.container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 2rem;
  background-color: #ecf0f1;
  height: 60vh;
}

.card {
  width: 25%;
  height: 100%;
  margin: 1rem;
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  overflow: hidden;
}

.card:hover {
  box-shadow: rgb(38, 57, 77) 0px 20px 30px -10px;
}

.card-image {
  width: 100%;
  height: 50%;
  overflow: hidden;
}

.card-image img {
  width: 100%;
}

.card-content {
  padding: 1rem;
}

.card-content h3 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  color: #34495e;
}

.card-content p {
  font-size: 1rem;
  color:#34495e;
}

</style>