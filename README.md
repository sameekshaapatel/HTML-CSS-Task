# HTML-CSS-Task
This task involves creating a simple webpage using HTML and CSS that incorporates various structural and styling elements. 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            color: navy;
        }
        p {
            font-family: "Georgia", serif;
            line-height: 1.6;
            text-align: justify;
            width: 50%;
            margin: 0 auto;
        }
        .image-container {
            text-align: center;
            margin: 20px 0;
        }
        .styled-button {
            padding: 10px 20px;
            border: 2px solid black;
            background-color: lightblue;
            cursor: pointer;
            transition: 0.3s;
        }
        .styled-button:hover {
            background-color: darkblue;
            color: white;
        }
        table {
            width: 50%;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        .form-container {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is the first paragraph. It introduces the content of the webpage.</p>
    <p>This is the second paragraph. It provides additional details.</p>
    
    <div class="image-container">
        <img src="image.png" alt="Sample Image" width="300">
        <p>Caption for the image</p>
    </div>
    
    <button class="styled-button">Click Me</button>
    
    <table>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
            <th>Column 3</th>
        </tr>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
            <td>Data 3</td>
        </tr>
        <tr>
            <td>Data 4</td>
            <td>Data 5</td>
            <td>Data 6</td>
        </tr>
    </table>
    
    <div class="form-container">
        <form>
            <input type="text" placeholder="Enter Name">
            <input type="email" placeholder="Enter Email">
            <button type="submit" class="styled-button">Submit</button>
        </form>
    </div>
</body>
</html>
