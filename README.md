    I AM CREATING MY FIRST WEBPAGE USING STYLE CSS HIHLIGHTING THE VARIOUS PLACES I LIKE TO VISIT.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my first webpage</title>
    <link rel="stylesheet" href="css/style.css">


</head>

<body>

</body>

</html>

h1{
    color: red;
    text-align: center;
    font-style: italic;
    font-weight: bold;
    font-family: Arial, sans-serif;
    font-size: 36px;
    line-height: 1.5;
}

body {
  background-color: #a567da;
  font-family: Verdana, sans-serif;
  margin: 20px;
}

p {
  color: #333;
  line-height: 1.6;
}

a {
  color: #0077cc;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Favorite Places</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <h1>Favorite Places to Visit</h1>
  
  <p>Here are some places I love:</p>
  
  <ul>
    <li>
      <a href="https://www.paris.fr">Paris</a>  
      <img src="images/paris.jpg" alt="Eiffel Tower" width="300">
    </li>
    <li>
      <a href="https://www.nps.gov/grca/">Grand Canyon</a>  
      <img src="images/grandcanyon.jpg" alt="Grand Canyon" width="300">
    </li>
  </ul>
  
  <p style="color: blue; font-weight: bold;">
    Inline style example: This text is blue and bold!
  </p>
</body>
</html>
