# KnowExtra

```
 In Python, the ++ operator is not defined as a binary operator. It's a common misconception, especially for those coming from languages like C++ or Java where ++ is used for incrementing.


 So What happened is, I was reading a book named 'Think Python' and in the first exercise , it was a question that why not try 2++2
 I tried it and Surprisingly as I typed it in my code editor , the operator '++' becomes Red!?
But the answer was coming correct as what is expected

And in programming is is also said that if your code works well wihout any error then don't interfare in it even if you don't konw the concept

But the concept of red colour is :
In Python, the ++ operator is not defined as a binary operator. It's a common misconception, especially for those coming from languages like C++ or Java where ++ is used for incrementing. In Python '++' operator is defined as a Unary Operator
 

![Screenshot From 2024-12-05 23-51-12](https://github.com/user-attachments/assets/7b42d829-9a36-4806-bc1e-062e2818441f)

```

```
Concept Of OCTAL NUMBERS

Imagine a situation using Conditional Statements:

if 1 == 01:
    print("True")
else:
   print("False")

Most people think the output will be a True, as in math 1==01 is True.
But the output is False because Here it is Python and It is an invalid operator in python

In code editor, The one (1) becomes the colour RED as it is an invalid Operator.

BUT forcefully if we want to Use 01 only only then Comes the concept Octal Numbers

We can use 0o1 instead of 01. That will be correct

if 1 = 0o1:
    print("True")
else:
   print("False")

THIS IS CORRECT

```

```

Suppose I write a variable and assign it a string value

flavour = "Apple Pie"

print(flavour[:])
Above code will return me the full string flavour

But unlike Indexing , python will not raise any TypeError if we exceed the limit of the index in the box bracket.

print(flavour[:100])
THIS WILL ALSO RETURN ME THE FULL STRING flavour.

```

```

We have studied INTEGERS AND FLOATS.
IN IDLE, PYTHON CAN EASILY HANDLE VERY LARGE INTEGERS, BUT SURPRISINGLY NOT FLOATS

THE MAXIMUM VALUE OUGHT TO BE WELL BEYOND MACHINES IS 2e400 WHICH IS 2*10^400

IF WE TYPE 2e400 IN IDLE, WE GET inf . I THINK THIS STANDS FOR INFINITE.

ALSO:

type(inf)   The type of inf comes to be float.

