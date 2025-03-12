<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML Program</title>
</head>
<body>
    <header>
        <h1>Welcome to My Simple HTML Program</h1>
    </header>

    <main>
        <p id="description">This is a simple webpage created using HTML.</p>
        <button onclick="changeText()">Click Me to Change Text</button>
    </main>

    <script>
        // JavaScript function to change the text content of the paragraph
        function changeText() {
            document.getElementById("description").textContent = "You clicked the button! The text has changed.";
        }
    </script>
</body>
</html>
