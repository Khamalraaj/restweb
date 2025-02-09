# Ex.07 Restaurant Website
## Date:22.12.2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

web.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maharaja's Feast</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#administration">Team</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Home Page -->
    <section id="home">
        <div class="banner">
            <div>
                <h1>Maharaja's Feast</h1>
            </div>
        </div>
        <main>
            <h2 class="section-title">Our Story</h2>
            <p>Welcome to Maharaja's Feast, where traditional Indian flavors meet modern culinary artistry. Our restaurant offers an authentic dining experience with carefully selected spices and fresh ingredients, bringing you the true taste of India.</p>
        </main>
    </section>

    <!-- Menu Page -->
    <section id="menu">
        <main>
            <h2 class="section-title">Our Menu</h2>
            <div class="menu-grid">
                <div class="menu-item">
                    <img src="chicken-butter-masala-recipe.jpg" alt="Butter Chicken">
                    <h3>Butter Chicken</h3>
                    <p> Butter Chicken is a classic Indian dish made with marinated & grilled chicken (Tandoori chicken), simmered in a creamy tomato gravy/curry.</p>
                </div>
                <div class="menu-item">
                    <img src="thalappakatti-chicken-biriyani-.jpg" alt="Biryani">
                    <h3>Dindigul Biryani</h3>
                    <p>Fragrant basmati rice with spiced meat and aromatics</p>
                </div>
                <div class="menu-item">
                    <img src="Mutton_Banjara_.jpg" alt="mutton banjara">
                    <h3>Rajasthani Style Mutton Banjara </h3>
                    <p> The easiest Mutton Curry made with simple ingredients along with a simple recipe.</p>
                </div>
                <div class="menu-item">
                    <img src="unnamed.jpg" alt="meals">
                    <h3>Thala vazhai ilai sappadu</h3>
                    <p>South Indian meals, a typical full meals as we call it thala vazhai ilai sappadu (South Indian banana leaf meals).</p>
                </div>
                <div class="menu-item">
                    <img src="mushroom2.jpg" alt="Stuffed mushroom">
                    <h3>Stuffed Mushrooms</h3>
                    <p>A traditionally non-Indian dish – Stuffed Mushrooms – but Indian-ified, duh! It's super simple, pretty fast, and great as a snack, light lunch, or appetizer!</p>
                </div>
                <div class="menu-item">
                    <img src="Madras_chickencurry-3.jpg" alt="Madras chicken">
                    <h3>Chicken Madras</h3>
                    <p>Chicken Madras Curry is a spicy, hot, tangy and slightly sweet curry that's believed to be inspired by the Tamil cuisine.</p>
                </div>
                <div class="menu-item">
                    <img src="maxresdefault.jpg" alt="Fish fry">
                    <h3>Kerala Fish Fry</h3>
                    <p>Coastal style fish curry with coconut</p>
                </div>
                <div class="menu-item">
                    <img src="Gulab-Jamun-Thumbnail.jpg" alt="Gulab Jamun">
                    <h3>Gulab Jamun</h3>
                    <p>Sweet milk dumplings in sugar syrup</p>
                </div>
                <div class="menu-item">
                    <img src="kaju.jpg" alt="halwa">
                    <h3>karupatti halwa</h3>
                    <p> Tirunelveli karupatti halwa is made up of karupati instead of sugar, Karupatti has rich calcium content and blood purifying properties. </p>
                </div>
            </div>
        </main>
    </section>

    <!-- Administration Page -->
    <section id="administration">
        <main>
            <h2 class="section-title">Our Team</h2>
            <div class="team-grid">
                <div class="team-member">
                    <img src="images.jpeg" alt="Head Chef">
                    <h3>Chef Koushik</h3>
                    <p>Head Chef</p>
                </div>
                <div class="team-member">
                    <img src="download.jpeg" alt="Restaurant Manager">
                    <h3>M.Balaji</h3>
                    <p>Restaurant Manager</p>
                </div>
                <div class="team-member">
                    <img src="images (1).jpeg" alt="Biriyani Expert">
                    <h3>jabbar bhai</h3>
                    <p>Biriyani expert </p>
                </div>
                <div class="team-member">
                    <img src="server.jpg" alt="Head Server">
                    <h3>Mukesh  Daniel</h3>
                    <p>Head Server</p>
                </div>
            </div>
        </main>
    </section>

    <!-- Contact Page -->
    <section id="contact">
        <main>
            <h2 class="section-title">Contact Us</h2>
            <div class="contact-info">
                <h3>Maharaja's Feast</h3>
                <p>42 Cana Lane<br>Spara District<br>Foodie City, FC 14645</p>
                <p>Phone: (555) 123-4567</p>
                <p>Email: info@Maharaja'sFeast.com</p>
                <p>Hours:<br>
                Tuesday - Sunday: 11:30 AM - 3:00 PM, 6:00 PM - 10:30 PM<br>
                Closed on Mondays</p>
            </div>
        </main>
    </section>

    <footer>
        <p>© 2024 Maharaja's Feast | Designed by Khamalraaj S[24901015] </p>
    </footer>
</body>
</html>

```
rest.css
```
/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

:root {
    --primary: #f64b08;
    --secondary: #F5DEB3;
    --accent: #FF6B6B;
    --text: #333333;
    --background: #FAFAFA;
}

/* Navigation */
nav {
    background-color: var(--primary);
    padding: 1rem;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 100;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 2rem;
}

nav a {
    color: white;
    text-decoration: none;
    font-size: 1.1rem;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    transition: all 0.3s ease;
}

nav a:hover {
    background-color: var(--accent);
    transform: translateY(-2px);
}

/* Banner */
.banner {
    height: 70vh;
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('Untitled design.png') center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    text-align: center;
    margin-top: 3.5rem;
}

.banner h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    animation: fadeIn 1.5s ease-out;
}

.banner p {
    font-size: 1.2rem;
    animation: slideUp 1.5s ease-out;
}

/* Main Content */
main {
    max-width: 1200px;
    margin: 2rem auto;
    padding: 0 1rem;
}

/* Menu Page */
.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    padding: 2rem 0;
}

.menu-item {
    background: rgb(230, 185, 169);
    padding: 1rem;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    overflow: hidden;
}

.menu-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

.menu-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
    transition: transform 0.3s ease;
}

.menu-item:hover img {
    transform: scale(1.05);
}

/* Administration Page */
.team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    padding: 2rem 0;
}

.team-member {
    text-align: center;
    background: white;
    padding: 1.5rem;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}

.team-member:hover {
    transform: translateY(-5px);
}

.team-member img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 1rem;
    border: 4px solid var(--primary);
    transition: transform 0.3s ease;
}

.team-member:hover img {
    transform: scale(1.1);
}

/* Contact Page */
.contact-info {
    background: white;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    max-width: 600px;
    margin: 2rem auto;
    transition: transform 0.3s ease;
}

.contact-info:hover {
    transform: translateY(-5px);
}

/* Footer */
footer {
    background: var(--primary);
    color: white;
    text-align: center;
    padding: 1.5rem;
    margin-top: 2rem;
}

/* Common Styles */
h2 {
    color: var(--primary);
    margin-bottom: 1.5rem;
    position: relative;
    display: inline-block;
}

h2::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    height: 2px;
    background: var(--accent);
    transform: scaleX(0);
    transition: transform 0.3s ease;
}

h2:hover::after {
    transform: scaleX(1);
}

.section-title {
    text-align: center;
    margin: 2rem 0;
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

@keyframes slideUp {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Responsive Design */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
        text-align: center;
    }
    
    .banner h1 {
        font-size: 2.5rem;
    }
    
    .menu-grid {
        grid-template-columns: 1fr;
    }
    
    .team-grid {
        grid-template-columns: 1fr;
    }
}
```


## OUTPUT:
![alt text](<Screenshot 2024-12-22 175134.png>)
![alt text](<Screenshot 2024-12-22 175146.png>)
![alt text](<Screenshot 2024-12-22 175225.png>)
![alt text](<Screenshot 2024-12-22 175234.png>)

## RESULT:
The program for designing Restaurant Website using HTML and CSS is completed successfully.
