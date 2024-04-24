## Infinite cycle is primarily used in games, applications and on different platforms

```
puts("The program has been started")
puts()

print("Enter your message: ")
message = gets().chomp()

while (message.size() > 0)
  print("Enter your message: ")
  message = gets().chomp()
end

puts()
puts("The program has been finished")
```
```
puts("The program has been started")
puts()

begin
  print("Enter your message: ")
  message = gets().chomp()
end while (message.size() > 0)

puts()
puts("The program has been finished")
```
```
puts("The program has been started")
puts()

begin
  print("Enter your message: ")
  message = gets().chomp()

  if (message.size() == 0)
    break
  end
  
  if (message.size() > 20)
    puts("Dude, you are such a chatterbox")
  else
    puts("Are you a guerrilla?")
  end
end while (message)

puts()
puts("The program has been finished")
```
