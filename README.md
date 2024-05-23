<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FLAVOUR FILES</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background-color: #ff6347;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #ff8c69;
            padding: 0.5rem 0;
            z-index: 1000;
        }

        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-size: 1.1rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .about-us {
            background-color: white;
            padding: 2rem;
            text-align: center;
        }

        .about-us h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .about-us p {
            font-size: 1.2rem;
            margin: 0 auto;
            max-width: 600px;
        }

        .our-recipes {
            text-align: center;
            padding: 2rem 0;
        }

        .our-recipes h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        

        html {
            scroll-behavior: smooth;
        }

        .container {
            display: flex;
            overflow-x: auto;
            scroll-snap-type: x mandatory;
            padding: 2rem;
            margin-bottom: 1rem;
            -webkit-overflow-scrolling: touch;
        }

        .recipe-card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 1rem;
            overflow: hidden;
            width: 300px;
            flex: 0 0 auto;
            scroll-snap-align: start;
        }

        .recipe-card img {
            width: 100%;
            height: auto;
        }

        .recipe-card h2 {
            font-size: 1.5rem;
            margin: 1rem;
        }

        .recipe-card p {
            margin: 0 1rem 1rem;
        }

        .recipe-card a {
            background-color: #ff6347;
            border: none;
            border-radius: 0 0 8px 8px;
            color: white;
            display: block;
            padding: 1rem;
            text-align: center;
            text-decoration: none;
        }

        .recipe-card a:hover {
            background-color: #ff4500;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }

        .scroll-btn {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background-color: rgba(255, 255, 255, 0.5);
            color: black;
            border: none;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            cursor: pointer;
            font-size: 1.5rem;
            z-index: 1000;
        }

        .scroll-btn-left {
            left: 0;
        }

        .scroll-btn-right {
            right: 0;
        }
        .user-photos {
    background-color: #f9f9f9; /* Background color to visually separate from recipe cards */
    padding: 2rem 0;
}

.user-photos h2 {
    text-align: center;
    margin-bottom: 2rem; /* Increase bottom margin for spacing */
}

.photo-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 1rem;
    padding: 0 2rem; /* Add horizontal padding to center the grid */
}

.photo-card img {
    width: 100%;
    height: auto;
}

.photo-card {
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

    </style>
</head>
<body>
    <header>
        <h1>FLAVOUR FILES</h1>
    </header>
    <nav>
        <a href="#about-us">Home</a>
        <a href="#our-recipes">Recipes</a>
        <a href="#userphotos">User Photos</a>
        <a href="#Contact">Contact</a>
    </nav>
    <section id="about-us" class="about-us">
        <h2>About Us</h2>
        <p>Welcome to Recipe Realms, your ultimate destination for discovering and sharing delicious recipes. Whether you're a culinary expert or a home cook, you'll find a wide variety of recipes to inspire your next meal. Join our community and start exploring today!</p>
    </section>
    <section id="our-recipes" class="our-recipes">
        <h2>Our Recipes</h2>
    </section>
    <div class="container">
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Delicious Pasta</h2>
            <p>A classic pasta recipe with tomato sauce and fresh basil.</p>
            <a href="https://example.com/recipe1" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Homemade Pizza</h2>
            <p>Make your own pizza with fresh ingredients and a crispy crust.</p>
            <a href="https://example.com/recipe2" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Chocolate Cake</h2>
            <p>A rich and moist chocolate cake perfect for any occasion.</p>
            <a href="https://example.com/recipe3" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Grilled Salmon</h2>
            <p>Delicious grilled salmon seasoned to perfection.</p>
            <a href="https://example.com/recipe4" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Veggie Stir-Fry</h2>
            <p>Healthy and flavorful vegetable stir-fry.</p>
            <a href="https://example.com/recipe5" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Classic Caesar Salad</h2>
            <p>A traditional Caesar salad with homemade dressing.</p>
            <a href="https://example.com/recipe6" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Grilled Salmon</h2>
            <p>Delicious grilled salmon seasoned to perfection.</p>
            <a href="https://example.com/recipe4" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Veggie Stir-Fry</h2>
            <p>Healthy and flavorful vegetable stir-fry.</p>
            <a href="https://example.com/recipe5" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Classic Caesar Salad</h2>
            <p>A traditional Caesar salad with homemade dressing.</p>
            <a href="https://example.com/recipe6" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Grilled Salmon</h2>
            <p>Delicious grilled salmon seasoned to perfection.</p>
            <a href="https://example.com/recipe4" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Veggie Stir-Fry</h2>
            <p>Healthy and flavorful vegetable stir-fry.</p>
            <a href="https://example.com/recipe5" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Classic Caesar Salad</h2>
            <p>A traditional Caesar salad with homemade dressing.</p>
            <a href="https://example.com/recipe6" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Homemade Pizza</h2>
            <p>Make your own pizza with fresh ingredients and a crispy crust.</p>
            <a href="https://example.com/recipe2" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Chocolate Cake</h2>
            <p>A rich and moist chocolate cake perfect for any occasion.</p>
            <a href="https://example.com/recipe3" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Grilled Salmon</h2>
            <p>Delicious grilled salmon seasoned to perfection.</p>
            <a href="https://example.com/recipe4" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Veggie Stir-Fry</h2>
            <p>Healthy and flavorful vegetable stir-fry.</p>
            <a href="https://example.com/recipe5" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Classic Caesar Salad</h2>
            <p>A traditional Caesar salad with homemade dressing.</p>
            <a href="https://example.com/recipe6" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Grilled Salmon</h2>
            <p>Delicious grilled salmon seasoned to perfection.</p>
            <a href="https://example.com/recipe4" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Veggie Stir-Fry</h2>
            <p>Healthy and flavorful vegetable stir-fry.</p>
            <a href="https://example.com/recipe5" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Classic Caesar Salad</h2>
            <p>A traditional Caesar salad with homemade dressing.</p>
            <a href="https://example.com/recipe6" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Grilled Salmon</h2>
            <p>Delicious grilled salmon seasoned to perfection.</p>
            <a href="https://example.com/recipe4" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Veggie Stir-Fry</h2>
            <p>Healthy and flavorful vegetable stir-fry.</p>
            <a href="https://example.com/recipe5" target="_blank">View Recipe</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Recipe Image">
            <h2>Classic Caesar Salad</h2>
            <p>A traditional Caesar salad with homemade dressing.</p>
            <a href="https://example.com/recipe6" target="_blank">View Recipe</a>
        </div>
        
    </div>
    <section id="user-photos" class="user-photos">
        <h2>User Photos</h2>
        <div class="photo-container">
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
            <div class="photo-card">
                <img src="https://via.placeholder.com/300x300" alt="User Photo">
            </div>
           
        </div>
    </section>
    <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Send us your photos to be featured in the user photos section!</p>
    <form id="photo-upload-form" enctype="multipart/form-data">
        <input type="file" name="photo" accept="image/*" required>
        <button type="submit">Upload Photo</button>
    </form>
</section>

    
    <button class="scroll-btn
    scroll-btn scroll-btn-left" onclick="scrollRecipes('left')">&#10094;</button>
    <button class="scroll-btn scroll-btn-right" onclick="scrollRecipes('right')">&#10095;</button>

    <script>
        function scrollRecipes(direction) {
            const container = document.querySelector('.container');
            const scrollAmount = 300;
            if (direction === 'left') {
                container.scrollBy(-scrollAmount, 0);
            } else if (direction === 'right') {
                container.scrollBy(scrollAmount, 0);
            }
        }
    </script>
    <footer>
        <p>&copy; 2024 FLAVOUR FILES. All rights reserved.</p>
    </footer>
    </body>
</html>
  
