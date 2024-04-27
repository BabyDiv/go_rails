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
```
animals = []
print("Enter number of animals you would like to describe: ")
n = gets().chomp().to_i()
i = 0
sum = 0
average_age = 0

while (i < n)
  puts("Create an animal")

  animal = {"species" => nil, "class" => nil, "name" => nil, "age" => nil}

  print("Enter a species: ")
  animal["species"] = gets().chomp()

  print("Enter a class: ")
  animal["class"] = gets().chomp()

  print("Enter a name: ")
  animal["name"] = gets().chomp()

  print("Enter age: ")
  animal["age"] = gets().chomp().to_i()

  animals.push(animal)

  sum += animal["age"]

  average_age = sum / n

  i = i + 1
end

puts("#{animals}")
puts(sum)
puts(average_age)
```
