```
def buy(m, x)
  if (m < 0)
    return "пиздюли"
  elsif (m == 0)
    return "воздух"
  elsif (m <= 10)
    return "полиэтиленовый пакет"
  elsif (m <= 1000000000)
    return "бмв м класс"
  else
    return "яхта абромовича"
  end
end

puts([ buy(-10, 0), buy(12, ), buy(99999999999) ])
```
