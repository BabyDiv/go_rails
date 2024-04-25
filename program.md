```
todo = []

puts("Welcome to TODO List App!")
puts("Menu:
1. Create TODO
2. Read TODOs
3. Update TODO
4. Delete TODO
0. Exit")


begin
  print("Please, choose one menu option: ")
  n = gets().chomp().to_i()
  if (n == 1)
    puts()
    puts("Create TODO")
    print("Please, enter your TODO text: ")
    todo.push( gets().chomp() )
    puts("Your TODO #{todo} has been successfully added")
  end
  
  if (n == 2)
    puts()
    puts("Read TODOs")
    puts("Your TODO list is #{todo}")
  end
  if (n == 3)
    puts()
    puts("Update TODO")
    print("Please, enter index of TODO you want to modify: ")
    i = gets().chomp().to_i()
    print("Change the value of the array: ")
    todo[i] = gets().chomp()
  elsif (n == 4)
    puts()
    puts("Delete TODO")
    print("Please, enter the number of TODO you want to delete: ")
    todo.delete_at( gets().chomp().to_i() )
    puts("Your TODO list is #{todo}")
  elsif (n == 0)
    puts("Exit")
    break
  end
end while (n <= 4)
```
