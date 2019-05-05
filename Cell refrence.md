# Absolute and Relative cell reference

## Relative To Relative (A1 , B1)

This is normal behavior of excel. When we copy formula to next cell the action moves relatively 

Meaning `=A1 * B1` Becomes `= A2 * b2` . and it go on like this.

## Absolute Cell Reference ($A $1)

To Get  `$A$1`  press `f4` key 

In This behavior of excel we will calculate the value of all cells in reference to one cell.

For example ,

We have One Row of numbers and we want to multiply them with the reference of cell.

```vbscript
5
10
15
20
25
30
35
40
45
50
55
60
65

```

Now we want all of these values to be multiplied by value in one cell lets say 

`3`

write this formula

`=A3*$A$1`  To Get  `$A$1`  press `f4` key 

## Absolute and Relative cell reference ($A1)

In Above Reference we multiply by only one cell 

But in this Reference we multiply by one Column. Always Refer to Specific Column for on Reference .

`=B1 * $A1`  

##  Relative and Absolute  cell reference (A$1)

This is Same as above formula but it works with Rows  

