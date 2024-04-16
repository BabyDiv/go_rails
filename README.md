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
