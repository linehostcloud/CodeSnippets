Abaixo o código detalhado

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background Gradient Animate</title>

    <style type="text/css">
        .background-animate {
            background: linear-gradient(
                to right, #833ab4, #fd1d1d, #fcb045
            );
            background-size: 400% 400%;
            animation: background-animate 10s infinite ease-in-out;
        }

        @keyframes background-animate {
            0% {
                background-position: 0 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0 50%;
            }
        }

    </style>
</head>
<body class="background-animate">
    
</body>
</html>
```