```
index = 0
while (index =! 1_000_000)
  puts(index)
  index = index + 1
end

index = 0
while (true)
  if (index == 1_000_000)
    break
  end

  puts(index)
  index = index + 1
end

index = 0
while (true)
  puts(index)
  index = index + 1

  if (index == 1_000_000)
    break
  end
end
```
```
$todo = []

def show_menu()
  puts("Welcome to TODO List App!")
  puts("Menu")
  puts("1. Create TODO")
  puts("2. Read TODOs")
  puts("3. Update TODO")
  puts("4. Delete TODO")
  puts("0. Exit")
end

def create_todo()
  puts()
    puts("Create TODO")
    print("Please, enter your TODO text: ")
    $todo.push( gets().chomp() )
    puts("Your TODO #{$todo} has been successfully added")
end

def read_todos()
  puts()
    puts("Read TODOs")
    puts("Your TODO list is #{$todo}")
end

def update_todo()
  puts()
  puts("Update TODO")
  print("Please, enter index of TODO you want to modify: ")
  i = gets().chomp().to_i()
  print("Change the value of the array: ")
  $todo[i] = gets().chomp()
end

def delete_todo()
  puts()
    puts("Delete TODO")
    print("Please, enter the number of TODO you want to delete: ")
    $todo.delete_at( gets().chomp().to_i() )
    puts("Your TODO list is #{$todo}")
end

show_menu()

begin
  print("Please, choose one menu option: ")
  n = gets().chomp().to_i()

  if (n == 1)
    create_todo()
  
  elsif (n == 2)
    read_todos() 
  
  elsif (n == 3)
    update_todo()

  elsif (n == 4)
    delete_todo()

  elsif (n == 0)
    puts("Exit")
    break
  end
end while (n <= 4 && n >= 0)
```
