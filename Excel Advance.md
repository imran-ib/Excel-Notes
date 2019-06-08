# Applying Formula in different sheets 

If we have more then one sheet and we want to add data in multiple sheets we can totally do that.

### Viewing two sheets side by side 

`view -> New window` and `View -> view side by side `

Now you should have two sheets side by side 

Write formula just like you normally would which is `=` and click the cell in deferent sheet you want to apply formula from. 

The formula in second sheet should be like this `=Sheet1!A4`

# Custom Date 

We know that we add date in sheet easily but sometimes we need more then just normal data.

we can change data format or set custom format

`right click -> format cells -> Number -> custom`

Here we can set any date format we like , for example `dddd, mmmm d, yyyy`

if we type date `7/31/2019` it will give us `Wednesday, July 31, 2019`

**Time is very similar to date **

Sometimes we may want to round up time to specific minutes. Previously we worked with three Round Functions.  `ROUND , ROUNDUP and ROUNDDOWN` But that will will not work with time.

We can use **MROUND** **FLOOR** and **CIELING** functions with time.

The function will take two arguments first is cell number with time we want to round and other is multiple(how many minutes we want to round).

`=MROUND(J11, "00:15")`

`=FLOOR(J10,"00:15")`

`=CEILING(J10,"00:15")`

All these functions will round time to 15 minutes 

#### Adding up Time 

If You want add up time just format cell of total to `[hh]:mm`

## Insert Image in excel

`insert -> illustrate -> image` 

There are three ways to Create Template in Excel 

Start from Scrach

Get And Existing Template and Tweak it according to your needs 

Get An Image and drop it on your sheet and work your way around it

**To Make a image background ** 

`format -> adjust -> color -> set background transparent ` click on any color you want to set transparent 

## Importing excel sheet to existing excel sheet 

`right click on the bottom sheet name and select move or copy `

check create copy 

select the sheet you want to copy to and click ok

## Converting Time to Decimal

Some times we need simple figure of hours and we may need to convert our time to decimal.

- Get  hours `=HOUR(A1)`
- Get Minutes `=MINUTE(B1)` 

The Actual Formula is simple `=A1*24` (hours in a day ) if you don't get decimal change format from custom to general 

# Conditional Foramtting

- Select the cell you want to format conditionally 
- `home -> styles -> conditional fotmatting`
- select New rule
- select the rule type
  - in this example we will select use formula 
- select the cell (use `f4` to select without any constant)
- Format it 

You can format cells with `format painter`

# Logical Test (if statement)

Will take three args, 

condition , 

if true , and 

if false

`=IF(A1=5,"YES","Nop")`

# Text Strings With Formula

We may want to merge string and numbers in same cell for example we want to get miles in cell and display`60 milse`

we can use Concatenate formula to do just that 

`=CONCATENATE(SUM(D31:J31), " Miles")`

If we need to display text in different format for example we have `27` and we want to show `$27.00`

we can set custom text formula 		`Text('L21',"$0.00")` OR `Text('L21',"dd mm yy")`  inside concatenate 



# Protecting the the cell 

`rightclick -> format cell -> protection  -> unchek the locked button`

`Review -> changes -> protect sheet`

# Vlookup

Looks for the value in the left most column in the table.

Works like search 

Takes 4 arguments 

- Lookup value
- Array of columns where to look for
- reference to the column where the value is populated
- Boolean weather the match should be exact or related 

`=VLOOKUP(A11,A2:B8,2,FALSE)`

# Text To Column

lets say we have an cell with full name and we want to split it into two columns one for first name and second for last name and original should be full name

`Select the column -> data -> text to column -> Select Delimited -> next -> select pace -> next -> Destination cell for first name -> finish`

# Copy row Text to Column 

`select and copt text in row -> right click -> spacial paste -> transpose`

