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

*Start from lacture 12*