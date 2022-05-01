# Logic calculator

## General info

This is a C++ program that converts given logic formula to its postfix representation (shunting yard algorithm) and then prints calculated result/s.

## Instruction

### Write a logic formula with up to 3 variables (p, q, r).

### Don't use spaces! Use only those characters:

* `0`
* `1`
* `p`
* `q`
* `r`
<br/>

* `~` - negation
* `v` - disjunction
* `^` - conjunction
* `I` - implication 
* `E` - equivalence
<br/>

* `(`
* `)`


## Examples:

Input
<pre>0v0E1^1</pre>

Output:
<pre>Result: 0</pre>

Input
<pre>~pEqE(~(pIq)^(qIp))</pre>

Output
<pre>
| p | q | result
| 0 | 0 | 1
| 0 | 1 | 0
| 1 | 0 | 1
| 1 | 1 | 1
</pre>
