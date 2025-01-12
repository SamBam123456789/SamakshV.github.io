<html>
<head>
    <title>Starbucks App</title>
    <script type="module" src="https://pyscript.net/alpha/pyscript.js"></script>
</head>
<body>
    <h1>Starbucks Order</h1>
    <py-script>
        print("Hello! Welcome to Starbucks")
        print("Today's menu is:")
        print("1. Small Coffee")
        print("2. Medium Coffee")
        print("3. Large Coffee")
        
        value = input("What would you like to order?")
        print(f"Here is your {value}.")
        
        payment_method = input("Would you like to pay with cash or card?")
        print(f"Payment method: {payment_method}.")
        print("Thank you for shopping at Starbucks. Have a great day!")
    </py-script>
</body>
</html>
