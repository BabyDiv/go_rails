```
a = [123, 2354, 45353, 2355, 23434, 243, 564432, 3242, 235425, 23545, 34545, 345, 3454, 3455, 43536]

index = 0
size = a.size()

while (index < size)
  puts("Элемент массива 'a' под порядковым номером #{index} равен #{a[index]}")
  index = index + 1
end
```

```
a = []

print("Enter n: ")
n = gets().chomp().to_i()
i = 0

while (i < n)
  print("> ")
  a[i] = gets().chomp().to_i()
  i = i + 1
end

puts()

puts("your array is: #{a}")

# Find sum of all numbers

i = 0
sum = 0

while (i < n)
  sum = sum + a[i]
  i = i + 1
  # puts("Iteration number is #{i}, sum is #{sum}")
end

min = a.min()
max = a.max()
average = sum / n

puts("Sum of all numbers is #{sum}")
puts("The smallest number in the array is #{min}")
puts("The biggest number in the array is #{max}")
puts("The average number in the array is #{average}")
```

```
a = []
print("Number of values in the array: ")
n = gets().chomp.to_i()
i = 0

while (i < n)
  print("> ")
  a[i] = gets().chomp().to_i()
  i = i + 1
end
puts()
i = 0
while (i < n)
  if (a[i] >= 0)
    puts(a[i])
  end
  i = i + 1
end

```
