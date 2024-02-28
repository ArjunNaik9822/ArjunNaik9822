<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1 id="head">this is java script</h1>
    <p id="demo">my name is karan</p>
    
    <button type="button" onclick="document.getElementById('demo').style.color='green'">click me</button>

    <script>
        let x = document.getElementById("head");

       x.style.color= "red";
    </script>
</body>
</html>
