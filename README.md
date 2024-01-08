# Innovasus.github.io
html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website Title</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Website Title</h1>
    </header>
    
    <main>
        <p>Welcome to my website!</p>
    </main>

    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>
"""

# Write the HTML content to a file
with open("index.html", "w") as file:
    file.write(html_content)

# Create a simple CSS file
css_content = """
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header, footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em;
}

main {
    padding: 2em;
}
"""

# Write the CSS content to a file
with open("styles.css", "w") as file:
    file.write(css_content)

print("Website files generated successfully.")
