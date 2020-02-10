# What I Learned in Week 3

## Week 3 was about booleans expressions, if statements, and Code Wars

### Boolean expressions
Boolean expressions are logical expressions that evaluate to the value `true` or `false`.  Logical expressions can be put together using NOT (`!`), OR (`||`), and AND (`&&`) operators.
- `!` - NOT.  Changes `true` to `false`, and `false` to `true`.
- `||` - OR: True if either operand is true.
- `&&` - AND: True if both operands are true.
- `===` - Strict equality: True if type and value of both operands are the same. `0` is not equal to `"0"`.
- `!==` - Strict inequality: Opposite of above.
- `==`  - Loose equality: True if the value of both operands is the same.  Uses type coercion if necessary. `0` is equal to `"0"`.
- `!=` Loose inequality: Opposite of above.
- `<` - Less-than: True if left operand is less than right operand.
- `<=` - Less-than-or-equal-to: True if left operand is less than or equal to right operand.
- `>` - Greater-than: True if left operand is greater than right operand.
- `>=` - Greater-than-or-equal-to: True if left operand is greater than or equal to right operand.

### IF-ELSE Statements
If/Else are conditional statements, which are a form of flow control.  If the expression in the `if` statement is true, the first block is run, otherwise the block after `else` is run.
```
let x = 1;
if(x) {
	return "x is 1";
} else {
	return "x is not 1";
}
```
### CODE WARS
[www.codewars.com](CodeWars) is a site where coding can be practiced using various coding challenges.  I created an account and practiced a bit.