# Calculate salary

4.17.2024

```
puts("I know that you are bad at Maths, but let's try to count your monthly salary")

def calculate_salary()
  print("Enter your daily payment: ")
  a = gets().chomp().to_i()

  s = a * 20
  h = a / 24

  print("When your daily payment is #{a}, your monthly salary is #{s} \n")
  print("When your daily payment is #{a}, you get #{h} per hour, tramp")
end

calculate_salary()
```
