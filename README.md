<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 40px;
        }
        h1 {
            font-size: 30px;
            font-weight: bold;
        }
        label {
            display: block;
            margin-top: 20px;
            font-size: 18px;
        }
        input[type="text"],
        input[type="email"],
        input[type="number"] {
            padding: 8px;
            font-size: 16px;
            width: 250px;
            margin-top: 5px;
        }
        input[type="submit"] {
            margin-top: 20px;
            padding: 8px 16px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <h1>Student Registration Form</h1>

    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" placeholder="Enter your full name">

        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="Enter your email">

        <label for="age">Age:</label>
        <input type="number" id="age" placeholder="Enter">

        <br>
        <input type="submit" value="Register">
    </form>

</body>
</html>
