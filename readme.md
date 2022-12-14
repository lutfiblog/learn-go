## Assign variable dapat menggunakan 2 cara:
1. menggunakan var
2. menggunakan shorthand := bila untuk changing value maka tiak menggunakan : hanya =

## Rules of naming Variables
- A variable name consists of alphabets, digits, and an underscore.
- Variables cannot have other symbols ( $, @, #, etc).
- Variable names cannot begin with a number.
- A variable name cannot be a reserved word as they are part of the Go syntax like int, type, for, etc.

|Data Types	| Description	| Examples|
|-----------|---------------|-----------|
|int	|Integer numbers.	|7123, 0, -5, 7023|
|float32 / float 64	|Numbers with decimal points. 	|20.2, 500.123456, -34.23|
|complex	|Complex numbers.	|2+4i, -9.5+18.3i|
|string	|Sequence of characters.	|"Hello World!", "1 is less than 2"|
|bool	|Either true or false.	| true, false|
|byte	|A byte (8 bits) of non-negative integers.	| 2, 115, 97|
|rune	|Used for characters. Internally used as 32-bit integers.	| 'a', '7', '<'|

## Data type in integer

|Data type	|Size|
|-----------|-----|
|int/uint	|either 32 bits (4 bytes) or 64 bits (8 bytes)|
|int8/uint8	|8 bits (1 byte)|
|int16/uint16	|16 bits (2 bytes)|
|int32/uint32	|32 bits (4 bytes)|
|int64/uint64	|64 bits ( 8 bytes)|

## Operator
|Operator	|Example|	Same as|
|-----------|--------|----------|
|+= (addition assignment)	|a += b	|a = a + b|
|-= (subtraction assignment)	|a -= b	|a = a - b|
|*= (multiplication assignment)	|a *= b	|a = a * b|
|/= (division assignment)	|a /= b	|a = a / b|
|%= (modulo assignment)	|a %= b		|a = a % b|

## Relational Operators
|Operator	|Example	|Descriptions|
|-----------|-----------|-------------|
|== (equal to)	|a == b	|returns true if a and b are equal|
|!= (not equal to)	|a != b	|returns true if a and b are not equal|
|> (greater than)	|a > b	|returns true if a is greater than b|
|< (less than)	|a < b	|returns true if a is less than b|
|>= (greater than or equal to)	|a >= b	|returns true if a is either greater than or equal to c|
|<= (less than or equal to)	|a <= b	|returns true is a is either less than or equal to b|

## Logical Operators
|Operator	|Description	|Example|
|-----------|---------------|-------|
|&& (Logical AND)	|exp1 && exp2	|returns true if both expressions exp1 and exp2 are true|
| (Logical OR) |exp1 OR exp2	|returns true if any one of the expressions is true.|
|! (Logical NOT)	|!exp	|returns true if exp is false and returns false if exp is true.|