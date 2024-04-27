```
cats = []

print('Enter number of cats: ')
n = gets().chomp().to_i()

iteration_number = 0
while (iteration_number < n)
  puts('Create a cat')

  cat = { "name" => nil, "age" => nil }

  print('Enter name: ')
  cat["name"] = gets().chomp()

  print('Enter age: ')
  cat["age"] = gets().chomp().to_i()

  cats.push(cat)

  iteration_number = iteration_number + 1
end

puts("#{cats}")


//-----


cats = []

print('Enter number of cats: ')
n = gets().chomp().to_i()

iteration_number = 0
while (iteration_number < n)
  puts('Create a cat')

  cat = { "name" => nil, "age" => nil }

  print('Enter name: ')
  cat["name"] = gets().chomp()

  print('Enter age: ')
  cat["age"] = gets().chomp().to_i()

  cats.puts(cat)

  iteration_number = iteration_number + 1
end

puts("#{cats}")
```
