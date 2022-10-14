
While Statement
*A while statement executes its statements as long as a specified condition evaluates to true. 
*If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
*The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

For Statement
*A for loop repeats until a specified condition evaluates to false. 
*When a for loop executes, the following occurs:
1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
4. If present, the update expression incrementExpression is executed.
5. Control returns to Step 2.

Assignment Opertator
Assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

Name				Shorthand operator		Meaning
Assignment			x = f()					x = f()
Addition assign	    x += f()			    x = x + f()
Subtraction assign  x -= f()			    x = x - f()
Multiplication      x *= f()				x = x * f()
Division assignment	x /= f()				x = x / f()
Remainder assign	x %= f()				x = x % f()
Exponentiation  	x **= f()				x = x ** f()
Left shift assign	x <<= f()				x = x << f()
Right shift assign	x >>= f()				x = x >> f()
Unsigned rightshift x >>>= f()		        x = x >>> f()
Bitwise AND     	x &= f()				x = x & f()
Bitwise XOR     	x ^= f()				x = x ^ f()
Bitwise OR  	    x |= f()			    x = x | f()
Logical AND     	x &&= f()				x && (x = f())
Logical OR  	    x ||= f()				x || (x = f())
Logical nullish 	x ??= f()				x ?? (x = f())



Comparison operator 
*compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or objects values.

Operator	Description	
Equal (==)		Returns true if the operands are equal.	
Not equal (!=)	Returns true if the operands are not equal.	
Strict equal (===)	Returns true if the operands are equal and of the same type. 
Strict not equal (!==)	Returns true if the operands are of the same type but not equal, or are of different type.	
Greater than (>)	Returns true if the left operand is greater than the right operand.	
Greater than or equal (>=)	Returns true if the left operand is greater than or equal to the right operand.	
Less than (<)	Returns true if the left operand is less than the right operand.	
Less than or equal (<=)	Returns true if the left operand is less than or equal to the right operand.	

