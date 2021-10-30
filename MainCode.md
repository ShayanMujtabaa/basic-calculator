<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Calculator</title>
</head>

<body>
    <h1>helloG</h1>
    <script>
        var num1 = parseInt(prompt("Enter the first number", ""))
        var num2 = parseInt(prompt("Enter the second number", ""))
        var operator = prompt("Please enter your operator", operator)

        function add(num1, num2) {
            return num1 + num2
            document.write(num1 + num2)
                //parseInt(num1 + num2)
                // var ans = parseInt(num1 + num2)
                //parseInt(ans)
                // parseInt(alert(num1 + num2))
                //document.write("The answer is " + ans)

        }

        function sub(num1, num2) {
            return num1 - num2
            document.write(num1 - num2)
        }

        function multi(num1, num2) {
            //return num1 * num2
            var ans = num1 * num2
            document.write(ans)
        }

        function divide(num1, num2) {
            //return num1 / num2
            var ans = num1 / num2
            document.write(ans)
        }


        if (operator == "+") {
            add()
        } else if (operator == "-") {
            sub()
        } else if (operator == "*") {
            multi()
        } else if (operator == "/") {
            divide()
        } else {
            document.write("The Operator you entered is incorrect")
        }
    </script>
</body>

</html>
