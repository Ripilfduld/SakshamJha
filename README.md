# SakshamJha
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Next Page</title>
    <style>
        /* Reset some default styles */
body, h1, h2, p {
    margin: 0;
    padding: 0;
}

/* Apply styles to the header */
header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

/* Style the navigation menu */
nav {
    background-color: #555;
    color: #fff;
    text-align: center;
    padding: 10px;
}

/* Style the container */
.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

/* Style the footer */
.footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}

/* Style links in the footer */
.footer a {
    color: #fff;
    text-decoration: none;
    margin: 0 5px;
}

    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Next Page</h1>
    </header>
    
    <nav>
        <!-- Your navigation menu here -->
    </nav>
    
    <div class="container">
        <h2>Thoughts Are : -</h2>
        
        <!-- You can add more content here as needed -->
    </div>
    
    <footer>
        <div class="footer">
            <a href="#" id="link1">Link</a> | <a href="#">Privacy Policy</a> | <a href="#">Help</a>
        </div>   
    </footer>

    <script>
        // JavaScript code to handle a click event on the "Link" element
        document.getElementById("link1").addEventListener("click", function() {
            alert("You clicked the Link!");
        });
    </script>
</body>
</html>
