<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Message</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            padding: 20px;
        }
        .welcome-message {
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            padding: 20px;
            max-width: 600px;
            margin: 0 auto;
            text-align: center;
        }
        .welcome-message h1 {
            font-size: 24px;
            color: #333333;
        }
        .welcome-message p {
            font-size: 16px;
            color: #666666;
            line-height: 1.6;
        }
    </style>
</head>
<body>

<div class="welcome-message" id="welcomeMessage"></div>

<script>
    const welcomeMessage = `
        <h1>🎨 Welcome to [AYOOLAADEGBAJU] Graphic Design! 🎨</h1>
        <p>Hello there! I’m thrilled to have you here. My name is <strong>Ayoola</strong>, 
        and I'm a passionate graphic designer dedicated to bringing your vision to life 
        through creative and impactful designs. Whether you're looking to revamp your brand, 
        create stunning visuals, or simply need a touch of inspiration, you've come to the right place!</p>
        <p>Let’s collaborate to turn your ideas into reality. Feel free to explore my portfolio, 
        request a custom design, or drop a message if you have any questions. I’m excited to work with you 
        and help your brand stand out in the best way possible!</p>
        <p>Cheers to creativity and collaboration,<br><strong>[CDA]</strong></p>
    `;

    getElementById('welcomeMessage').innerHTML = welcomeMessage;
</script>

</body>
</html>

<!---
Blaqperico/Blaqperico is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
