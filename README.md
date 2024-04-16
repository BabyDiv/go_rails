# go_rails

ruby - interpreter (tests programs)

irb - repl (a program that tests functions)

puts - выводмт в терминал

puts("Hello, \"World\" ") - нужно экранировать

puts("Hello, 'World' ") - не нужно экранировать

irb - exit - clear

puts("2 + 2 = 4")

2 + 2 = 4

=> nil

puts("2 + 2 = #{2 + 2}")
 
2 + 2 = 4

=> nil

"2 + 2 = #{2 + 2}"

hashes

=> "2 + 2 = 4"

'2 + 2 = #{2 + 2}'

=> "2 + 2 = \#{2 + 2}"

HASHES

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

MASSIVES

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

Условные операторы

salary = 10000

if salary < 10000

  puts("I'll find another job")
  
else

  puts("May be I will try")
  
end
