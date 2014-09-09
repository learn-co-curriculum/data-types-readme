---
tags: readme
language: ruby
resources: 1
track: web development
topic: ruby
unit: hello world
lesson: data types
---

# Data Types

## Introduction

Just like there are words, numbers, lists, etc. in English, there are Strings, Integers, Arrays, etc. in Ruby. These are different types of data, also known as classes. Ruby has several built-in classes and you'll learn how to make your own classes later on.

To find the class of something, you can just call `.class` on it. In Ruby,

Classic Examples:

| Class | Example | Syntax |
|-------|---------|--------|
| String | "hello" | quotation marks on either end |
| Fixnum | 9 | whole, non-decimal number |
| Float | 9.1 | decimal number |
| Array | [1,2,3] | comma-separated values surrounded by square brackets
| Hash  | {:president => "Obama", :vp => "Biden"} | keys that point to values using hashrockets (=>), separated by commas, surrounded by curly brackets

Deep Cut Examples:

| Class | Example | Syntax |
|-------|---------|--------|
| Nil | nil | The word nil not surrounded by any quotes (then it would be a string!)|
| Class | nil.class.class | Don't worry too much about this one!

If you don't know what class some data type is, you can just call `.class` on it. 

For instance:
```ruby
"Hello world".class
# => String

7.class
# => Fixnum

5.8.class
# => Float

["panda", "sloth", "sugar glider"].class
# => Array

{:panda => "bamboo", :sloth => "Cecropia trees"}.class
# => Hash

nil.class
# => NilClass

Class.class
# => Class
```

## Resources
* [RailsBridge](http://docs.railsbridge.org) - [Data Types](http://docs.railsbridge.org/ruby/datatypes)
