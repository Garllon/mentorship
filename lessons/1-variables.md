# Lesson 1 - Variables - DataTypes

- [Variables](#variables)
  - [Number](#number)
  - [Text(String)](#textstring)
  - [List(Array)](#listarray)
- [DataTypes](#datatypes)
- [Examples](#examples)

## Variables

Every practical programming language has a feature called variables.
This is basically the same concept that you might know from math, although in
Ruby there are different kinds of variables (you will get to know another one in
a couple lessons).

In Ruby you can assign a name to something (an object) by using the so called
assignment operator =. On the left side you have the variable name and on the
right side, what you like to assign.

### Number

Define an number.
```ruby
# A number
number = 1
```

Calculcate with numbers.
```ruby
number1 = 5
number2 = 10

# Use the + operator
result = number1 + number2
puts result 
# => 15

# Use the / operator
result = number1 / number2
puts result 
# => 0
```

Why is the last result 0 instead of 0.5 as expected?
Integer is limited to whole numbers. If we want to do this operation correctly then
we need floating point numbers. So the same operation as before, except this time
we define the numbers as floats.

```ruby
number1 = 10.0
number2 = 5.0

# Use the / operator
result = number1 / number2
puts result 
# => 0.5
```

Why not always use floats you ask? Floats need more
resources and we like to optimize code.
Think power usage. Your smartphone can live longer before you need to recharge. :)

### Text(String)

```ruby
# A Text
text = 'Hallo World'
```

You can also merge two texts together:
```ruby
# One Text
text1 = 'Hello'
text2 = 'World'
puts text1 + text2
```

### List(Array)

```ruby
# Merge different things together like fruits and vegetables
fruits = ['Apple','Orange']
vegetables = ['Cucumber', 'Tomate']

basket = fruits + vegetables

# Remove fruits from basket
basket = ['Apple', 'Tomate', 'Orange']
fruits = ['Orange', 'Apple']

basket = basket - fruits
```

#### Use the index of lists
With the following command we get the first element of the array.
```ruby
puts fruits[0]
# => 'Orange'

```

## DataTypes

- Number (Integer, Float, ..)
- Text (String)
- List (Array)
- Boolean (true/false) Will be handled in lesson-2
- Nil (Nothing, Empty)

## Examples

[Ruby - Variables](/lessons/examples/1_variables.rb)
