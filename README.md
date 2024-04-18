# go rails

## Section 1

ruby - interpreter (tests programs)

irb - repl (a program that tests functions)

puts - выводмт в терминал

puts("Hello, \"World\" ") - нужно экранировать

puts("Hello, 'World' ") - не нужно экранировать

irb - exit - clear

```

puts("2 + 2 = 4")

2 + 2 = 4

=> nil

puts("2 + 2 = #{2 + 2}")
 
2 + 2 = 4

=> nil

"2 + 2 = #{2 + 2}"

```

=> "2 + 2 = 4"

'2 + 2 = #{2 + 2}'

=> "2 + 2 = \#{2 + 2}"

## Hashes

```

songs = {"jackson" => "Dangerous", "osbourne" => "I just want you", "syrus" => "flowers"}

=> {"jackson"=>"Dangerous", "osbourne"=>"I just want you", "syrus"=>"flowers"}

songs

=> {"jackson"=>"Dangerous", "osbourne"=>"I just want you", "syrus"=>"flowers"}

songs["jackson"] = key

=> "Dangerous"

songs.size

=> 3

songs = {"jackson" => ["Dangerous", "Liberian girl", "Whatever happens"], "osbourne" => "I just want you", "syrus" => "flowers"}

=> {"jackson"=>["Dangerous", "Liberian girl", "Whatever happens"], "osbourne"=>"I just want you", "syrus"=>"flowers"}

songs["jackson"]

=> ["Dangerous", "Liberian girl", "Whatever happens"]

songs["jackson"].join(", ")

=> "Dangerous, Liberian girl, Whatever happens"

pets = { "dog" => {"name" => "Spot"}, "cat" => {"name" => "Yarn"} }

=> {"dog"=>{"name"=>"Spot"}, "cat"=>{"name"=>"Yarn"}}

pets["dog"]

=> {"name"=>"Spot"}

pets["dog"]["name"]

=> "Spot"

pets.dig("dog", "name")

=> "Spot"

```

## Arrays

```

characters = [{"name" => "The Little Mermaid", "age" => 18, "marital status" => "single"},{"name" => "Snow White", "age" => 16, "marital status" => "single"}]

=> [{"name"=>"The Little Mermaid", "age"=>18, "marital status"=>"single"}, {"name"=>"Snow White", "age"=>16, "marital status"=>"single"}]

characters[0]["age"]

=> 18

characters[0]["age"]+characters[1]["age"]

=> 34

print

gets = берет значение из print

print("What's your name?")

name = gets().chomp()

puts=("that is cool, #{name}")

## If else

salary = 10000

if salary < 10000

  puts("I'll find another job")
  
else

  puts("May be I will try")
  
end

```

## Conditionals

```

puts("

  Добро пожаловать в службу поддержки клиентов компании 'СуперТел'.
  
  1. Чтобы узнать больше о наших услугах, нажмите 1.
  
  2. Если у вас возникли проблемы с подключением услуг, нажмите 2.
  
  3. Если у вас есть вопросы о счетах и оплате, нажмите 3.
  
  4. Если вы хотите поговорить с оператором, нажмите 0 или просто оставайтесь на линии.

")

print("> ")

response = gets().chomp()

puts("Вы нажали #{response}")

if response == "1"

  puts("Узнать больше о наших услугах")

elsif response == "2"
 
  puts("Подключить услугу")

elsif response == "3"

  puts("Вопросы о счетах и оплате")

elsif response == "0"
 
  puts("Связаться с оператором")

else
 
  puts("Неправильный вариант ответа. Попробуйте еще раз")

end

```

## Loops and blocks

Операторы цикла

```

index = 0 - переменная

while index < 10 - оператор цикла

puts(index)

index = index + 1 - тело цикла

end
```
