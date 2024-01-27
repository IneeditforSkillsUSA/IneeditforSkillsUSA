<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fall Fest</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff7e5f;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }

        .attractions {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .attraction {
            width: 30%;
            margin-bottom: 20px;
            background-color: #fff;
            padding: 10px;
            border-radius: 5px;
        }

        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
        }

        input,
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        button {
            background-color: #ff7e5f;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #ff603f;
        }
    </style>
</head>

<body>

    <header>
        <h1>Fall Fest 2024</h1>
        <p>Join us for a celebration of all things autumn!</p>
    </header>

    <section>
        <h2>Event Information</h2>
        <p>Date: October 15th, 2024</p>
        <p>Time: 10:00 AM - 6:00 PM</p>
        <p>Location: [Your Venue Name], [City]</p>
    </section>

    <section>
        <h2>Attractions</h2>
        <div class="attractions">
            <div class="attraction">
                <h3>Pumpkin Patch</h3>
                <p>Pick your own pumpkins!</p>
            </div>
            <div class="attraction">
                <h3>Live Music</h3>
                <p>Enjoy the sounds of fall with live music performances.</p>
            </div>
            <div class="attraction">
                <h3>Food Trucks</h3>
                <p>Delicious autumn-inspired treats.</p>
            </div>
            <!-- Add more attractions as needed -->
        </div>
    </section>

    <section>
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </section>

</body>

</html>
