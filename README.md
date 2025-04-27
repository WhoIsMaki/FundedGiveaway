# FundedGiveaway
<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundedgiveaway</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Fundedgiveaway</h1>
        </div>
    </header>

    <section class="intro">
        <h2>Dobrodošli na Fundedgiveaway!</h2>
        <p>Uzmite svoju priliku za osvajanje fantastičnih nagrada! Prijavite se i sudjelujte u našem giveawayu.</p>
    </section>

    <section class="form-section">
        <h3>Prijavite se za Giveaway</h3>
        <form id="giveaway-form">
            <label for="name">Ime:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="social">Koja društvena mreža:</label>
            <select id="social" name="social">
                <option value="facebook">Facebook</option>
                <option value="instagram">Instagram</option>
                <option value="twitter">Twitter</option>
            </select>

            <button type="submit">Prijavite se</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Fundedgiveaway | Svi prava pridržana</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #4CAF50;
    padding: 20px;
    text-align: center;
    color: white;
}

h1 {
    font-size: 36px;
}

.intro {
    text-align: center;
    padding: 40px 20px;
    background-color: #fff;
    margin: 20px 0;
}

h2 {
    font-size: 28px;
    color: #333;
}

p {
    font-size: 16px;
    color: #666;
}

.form-section {
    text-align: center;
    padding: 20px;
    background-color: #fff;
    margin: 20px 0;
}

h3 {
    font-size: 24px;
    margin-bottom: 20px;
}

form {
    display: inline-block;
    text-align: left;
    background-color: #fafafa;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

label {
    display: block;
    margin-bottom: 10px;
    font-size: 16px;
}

input, select, button {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    background-color: #4CAF50;
    color: white;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #45a049;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

