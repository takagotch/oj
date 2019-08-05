### oj
---
https://github.com/ohler55/oj

```rb
require 'oj'
h = { 'one' => 1, 'array' => [ true, false ] }
json = Oj.dump(h)

h2 = Oj.load(json)
puts "Same? ${h == h2}"

gem 'oj'
```

```sh
gem install oj
```

```
```


