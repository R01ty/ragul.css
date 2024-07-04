#html 
OBJECTIVE:
To Create a simplified clone of Dribbble landing page.

DESCRIPTION:
Created a simplified clone of Dribble Landing Page With the use of HTML and CSS

HTML CODE:
```c
Style.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #000000;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #000000;
    padding: 10px 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.logo {
    font-family: monospace;
    font-size: 24px;
    font-weight: italic;
    color: #ff0000;
}

nav ul {
    justify-content: center;
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
    color: #ffffff;
}

.auth-buttons {
    display: flex;
}

.auth-buttons button {
    margin-left: 10px;
    padding: 5px 10px;
    border: none;
    cursor: pointer;
}

.auth-buttons .sign-in {
    background-color: #ffffff;
    color: #ea4c89;
    border: 1px solid #ea4c89;
}

.auth-buttons .sign-up {
    background-color: #ea4c89;
    color: #ffffff;
}

.hero {
    text-align: center;
    padding: 50px 20px;
    background-color: #ff0000;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 20px;
}

.hero h1 {
    margin: 0 0 10px;
    font-size: 36px;
}

.hero p {
    margin: 0;
    font-size: 18px;
    color: #666;
}
nav ul {
    justify-content: center;
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
    color: #ffffff;
}

.shots {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: 20px;
}

.shot {
    margin: 10px;
}

.shot img {
    width: 200px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

Page.html
```
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">Dribble</div>
        <nav>
            <ul>
                <li><a href="#">Inspiration</a></li>
                <li><a href="#">Find Work</a></li>
                <li><a href="#">Learn Design</a></li>
                <li><a href="#">Go Pro</a></li>
                <li><a href="#">Marketplace</a></li>
            </ul>
        </nav>
        <div class="auth-buttons">
            <button class="sign-in">Sign In</button>
            <button class="sign-up">Sign Up</button>
        </div>
    </header>

    <main>
        <section class="hero">
            <h1>Discover the world's top designers & creatives </h1>
            <p>Dribble is the leading destination to find & showcase creative work and home to the world's best design professional.</p>
        </section>
        <section>
            <nav>
                <ul>
                    <li><a href="#">Popular</a></li>
                    <li><a href="#">Shots</a></li>
                    <li><a href="#">Now</a></li>
                </ul>
            </nav>
        </section>

        <section class="shots">
            <!-- Example shot thumbnails -->
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 1.jpg" alt="Design Shot 1">
            </div>
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 2.png" alt="Design Shot 2">
            </div>
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 3.jpg" alt="Design Shot 3">
            </div>
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 4.jpg" alt="Design Shot 4">
            </div>
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 5.png" alt="Design Shot 5">
            </div>
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 6.png" alt="Design Shot 6">
            </div>
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 7.png" alt="Design Shot 7">
            </div>
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 8.jpg" alt="Design Shot 8">
            </div>
            <div class="shot">
                <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 9.gif" alt="Design Shot 9">
            </div>
            <div class="shot">
                 <img src="C:\Users\Lenovo\Downloads\amazon images\amazon 10.png" alt="Design Shot 10">
            </div>
        </section>
    </main>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-07-03 144623-1.png>)
 

