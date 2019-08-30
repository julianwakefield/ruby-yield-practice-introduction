# Yield Practice

In Ruby, code can be contained inside what is known
as a _block_. Blocks are typically attached to a method
call and contain code we're written that we want to be
performed as part of that method. For instance,
we can use the `each` method on an array. The `each` method
will iterate over every element in the array and do
something. That _something_ is defined within a block that
we provide:


```ruby
['a','b','c'].each do |letter|
  puts letter
end
```

In this case, our block is defined using `do..end`. Everything
in between is executed as part of the block.

`yield` is a Ruby keyword that can _call_ a block and we can use 
`yield` in our own methods to control exactly when a block is called.
In this section are lessons and labs on yield that cover topics
including:

* How to use yield
* Using yield in conjunction with loops
* Creating our own versions of common Ruby enumerables

Yield can be a complicated topic to understand but makes it 
possible to pass both parameters _and_ a block into any
method we create. In addition to the upcoming lessons, here 
are some resources you may find helpful:

* [Yield](https://rubymonk.com/learning/books/4-ruby-primer-ascent/chapters/18-blocks/lessons/54-yield)
* [The Yield Keyword in Ruby](https://medium.com/rubycademy/the-yield-keyword-603a850b8921)
* [Master Ruby Blocks in Less Than 5 Minutes](https://mixandgo.com/learn/mastering-ruby-blocks-in-less-than-5-minutes)
