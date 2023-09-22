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
  
