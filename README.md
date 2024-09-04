<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ce Client | cevr</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #000; 
        }
        
        .background {
            position: relative;
            width: 100%;
            height: 100%;
            overflow: hidden;
        }
        
        .gif-container {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3I5ZGllcXV1YjZ0eW13cGloMTY4djM4aXdzOGUwZTdlN3ZzcGJ0OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/0FweJstPNWLf4T2nIe/giphy.gif');
            background-size: cover;
            z-index: 1;
        }
        
        img {
            position: relative;
            border-radius: 50%;
            z-index: 2;
            width: 150px; 
            height: 150px; 
            border: 5px solid magenta;
            position : absolute;
            top : 30%;
        }
        h1 {
            color : white;
            font-family : 'Courier New', Courier, monospace;
            position : absolute;
            top : 45%;
            z-index : 2;
        }
        h2 {
            color : white;
            font-family : 'Courier New', Courier, monospace;
            position : absolute;
            top : 50%;
            z-index : 3;
            font-size : 24px;
        }
    </style>
</head>
<body>
    <div class="gif-container"></div>
    <img src="https://cdn.discordapp.com/avatars/1201357451291799552/8732c8f42e917d3d094ed6d64225ab7a.webp?size=4096">
    <h1>Cevr</h1>
    <h2>Website Dev and Owner for Ce Client</h2>
</body>
</html>
