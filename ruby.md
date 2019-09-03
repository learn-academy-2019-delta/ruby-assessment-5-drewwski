# ASSESSMENT 4: INTRO TO RUBY
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own there is always something more to learn.   

1. In what ways are JavaScript and Ruby similar? In what ways are they different?

  Your answer: Both are object oriented languages. Javascript uses curly's and ruby uses "end"

  Researched answer: JavaScript and Ruby are object-oriented, dynamic and general purpose scripting language which is interpreted rather than compile during runtime. JavaScript can be used as front-end and back-end language using the same language whereas Ruby is used as back-end programming language.



2. What is a hash?

  Your answer: a collection of keys and their values

  Researched answer: A Hash is a dictionary-like collection of unique keys and their values. Also called associative arrays, they are similar to Arrays, but where an Array uses integers as its index, a Hash allows you to use any object type. Hashes enumerate their values in the order that the corresponding keys were inserted.



3. What is the testing framework used in Ruby? Describe the process of setting up the testing environment.

  Your answer: RSPEC. Create an RSPEC file in the folder

  Researched answer: RSpec is a testing tool for Ruby, created for behavior-driven development (BDD). It is the most frequently used testing library for Ruby in production applications. Even though it has a very rich and powerful DSL (domain-specific language), at its core it is a simple tool which you can start using rather quickly.



4. Name three possible relationships between objects?

  Your answer: is_a, has_a, 

  Researched answer: kind_of, instance_of, is_kind_of



5. What is an instance variable? How is it different from other variables in Ruby?

  Your answer: variable with @

  Researched answer: An instance variable has a name beginning with @ , and its scope is confined to whatever object self refers to. Two different objects, even if they belong to the same class, are allowed to have different values for their instance variables.



6. Ruby has a great community and tons of free resources to help you learn. [Here](https://www.ruby-lang.org/en/documentation/)is a list of great resources. Below are a few popular ones:
- [Interactive Ruby Tutorial](http://tryruby.org/levels/1/challenges/0)
- [Why's (poigniant) Guide to Ruby](http://poignant.guide/book/chapter-1.html): comics, anecdotes, and microscopic canaries
- [Ruby in 20 Min](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Ruby Style Guide](https://rubystyle.guide/)

Choose one of these resources and look through the material for 10-15 min. List three new things you learned about Ruby:

1) "for double quotes do /"this"/ around the quotes"

2)%w[one two three].join(', ')
# => 'one, two, three'

3)Always use parentheses when calling super with arguments:
# bad
super name, age

# good
super(name, age)


7. Stretch: What are blocks, procs, and lambdas?

  Your answer:

  Researched answer:
