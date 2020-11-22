---
Layout: default
---

# Ruby

For a few years, Ruby has been my primary programming language. It is a very
versatile language, that can be used for simple shell scripts just as well as
for designing complex software architectures.

Ruby is an object oriented, general purpose programming language that is very
well suited for web development. It is dynamically typed and puts a big emphasis
on code readability. I like the elegance of well written Ruby code and the
powerful testing frameworks that exist for Ruby.

## Libraries

- [Sneakers](https://github.com/jondot/sneakers) - A fast background processing framework for Ruby and RabbitMQ
- [RSpec](https://rspec.info/) - Behaviour Driven Development for Ruby. Making TDD Productive and Fun.
- [Sequel](https://github.com/jeremyevans/sequel) - The Database Toolkit for Ruby
- [oj](https://github.com/ohler55/oj) - Optimized JSON

## Frameworks

- [Sinatra](http://sinatrarb.com/) - Great framework for building http based APIs
- [Hanami](https://hanamirb.org/) - Ruby framework with strong opinions about code structure
- [Rails](https://rubyonrails.org/) - The most popular MVC framework for Ruby. Mostly suited for monolithic websites. I rarely use it

## Code Snippets

### Round time down to a given interval

```
FIFTEEN_MINUTES = 15 * 60
t = Time.new # 2020-11-20 11:17:22 +0100

rounded_time = t - t.to_i % FIFTEEN_MINUTES # 2020-11-20 11:15:00 +0100
```
