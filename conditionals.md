```
x = 20

while (x < 100)
  puts(x)
  x = x + 10
end
```

```
puts("English, motherfucker, DO YOU SPEAK IT?")
puts("1. Yes")
puts("2. No")

print("> ")
response = gets().chomp().to_i()

if (response == 1)
  puts("Good job")
else
  puts("Loser. Fuck you you're fuckin' fuck")
end
```

```
number_of_bottles = 7

while (number_of_bottles > 0)
  if (number_of_bottles == 1)
    puts("I don't want to drink anymore")
  else
    puts("I'm thirsty. I want to drink #{number_of_bottles} bottles of Cola")
  end
  number_of_bottles = number_of_bottles - 1
end
```

