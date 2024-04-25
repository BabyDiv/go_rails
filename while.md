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
