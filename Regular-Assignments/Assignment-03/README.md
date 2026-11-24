# Assignment No. 3
# Check whether a triangle is right angled using a function

def right_triangle(a, b, c):
    # Check if the triangle satisfies Pythagoras theorem
    if a * a + b * b == c * c:
        return "Triangle is right angled"
    elif a * a + c * c == b * b:
        return "Triangle is right angled"
    elif b * b + c * c == a * a:
        return "Triangle is right angled"
    else:
        return "Triangle is not right angled"


# Taking input from user
a = int(input("Enter number 1: "))
b = int(input("Enter number 2: "))
c = int(input("Enter number 3: "))

# Calling the function
result = right_triangle(a, b, c)

# Displaying result
print(result)
