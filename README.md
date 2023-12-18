# crypto
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>javascript crypto API</h1>
    <br>
    <p id="demo"></p>
    <script>
        const myArray = new Uint32Array(10);
        let text = "";
        crypto.getRandomValues(myArray);
        
        for (const num of myArray){
            text += num + "<br>"
        }
        document.getElementById("demo").innerHTML =text;
    </script>
</body>
</html>
