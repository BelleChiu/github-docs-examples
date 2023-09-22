# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ use Codeblocks whenever possible.

Because it allows others to copy and pasta their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backtricks(`)
- Not to be confused with qoutation(')

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Prompt the user for input
print "Enter a number: "
number = gets.chomp.to_i

result = factorial(number)
puts "The factorial of #{number} is #{result}."

```
- When you can you should attempt to apply syntax highlighting to your codeblocks
```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Prompt the user for input
print "Enter a number: "
number = gets.chomp.to_i

result = factorial(number)
puts "The factorial of #{number} is #{result}."

```
This is my desktop background image

<img src="https://github.com/BelleChiu/github-docs-examples/assets/49231741/3c4dcd84-1df5-4008-be5a-f485f91a0642" alt="Image" width="300" height="200">

Good Cloud Engineerings use codeblocks for both Code and Errors that appear in the Console.

```bash
Traceback (most recent call last):
        2: from /usr/bin/irb:11:in `<main>'
        1: from (irb):1
NameError (undefined local variable or method `some_value' for main:Object)
irb(main):002:0>
```
> Here is an example of using a codeblock for an error that appears in bash




