<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HARRY POTTER</title>
    <style>
        /* Set the body to use full viewport height */
        body, html {
            margin: 0; /* Remove default margin */
            height: 100%; /* Set height to 100% to fill the viewport */
            overflow: hidden; /* Prevent scrolling */
        }

        /* Style for the container */
        .image-container {
            display: flex;
            flex-direction: column; /* Stack images vertically */
            height: 100%; /* Full height */
            overflow: hidden; /* Prevent overflow */
        }

        /* Style for images */
        img {
            width: 100%; /* Make the images fill the width of the container */
            height: auto; /* Maintain aspect ratio */
            max-height: 100vh; /* Ensure images do not exceed viewport height */
            object-fit: cover; /* Cover the area */
            margin-bottom: 0; /* No bottom margin for wallpapers */
        }
    </style>
</head>
<body>
    <div class="image-container">
        <img src="https://wallpapercave.com/wp/wp2900106.jpg" alt="Harry Potter Image 1">
        <img src="https://wallpaperaccess.com/full/22917.jpg" alt="Harry Potter Image 2">
        <img src="http://www.pixelstalk.net/wp-content/uploads/2016/01/Harry-Potter-7-Wallpapers-HD.jpg" alt="Harry Potter Image 3">
        <img src="https://wallpapertag.com/wallpaper/full/1/0/4/414328-full-size-harry-potter-desktop-backgrounds-1920x1080.jpg" alt="Harry Potter Image 4">
        <img src="https://wallpapercave.com/wp/wp3067512.jpg" alt="Harry Potter Image 5">
    </div>
</body>
</html>
