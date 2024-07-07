try:
    name = input("What is your name?: ")
    age = int(input("How old are you?: "))

    age += 1

    print(f"Hello, {name}! Next year, you will be {age} years old.")
except EOFError:
    print("Unexpected end of input. Please make sure to provide the required information.")
except ValueError:
    print("Invalid input. Please enter a valid number for age.")

