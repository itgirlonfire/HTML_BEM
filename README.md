index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>BEM Example</title>
</head>
<body>
    <div class="card">
        <img src="https://via.placeholder.com/300" alt="Sample Image" class="card__image">
        <h2 class="card__title">Card Title</h2>
        <p class="card__description">This is a description of the card content.</p>
        <button class="button card__button card__button--primary">Learn More</button>
    </div>
</body>
</html>

styles.css
body {
    font-family: Arial, sans-serif;
    background-color: #f8f8f8;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.card {
    background-color: #ffffff;
    border: 1px solid #dddddd;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    padding: 20px;
    max-width: 300px;
    text-align: center;
}

.card__image {
    max-width: 100%;
    border-radius: 8px;
}

.card__title {
    font-size: 1.5rem;
    margin: 15px 0;
}

.card__description {
    font-size: 1rem;
    color: #555555;
    margin: 10px 0 20px;
}

.button {
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    color: #ffffff;
    cursor: pointer;
    text-transform: uppercase;
    font-weight: bold;
    transition: background-color 0.3s;
}

.card__button {
    width: 100%;
}

.card__button--primary {
    background-color: #007bff;
}

.card__button--primary:hover {
    background-color: #0056b3;
}
