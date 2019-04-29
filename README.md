# Excel Notes

- We can use the key `f12` to save as the file

- We can use text in cell `strikethrough scubscript superscript` in format cell options.

- When we write data in cell and change it later the format of cell remain same. You have to change format manually.

  - For Example you Enter string `abc` in a cell and later you change it to `123` the format of cell do not change you have to change it to `number`

- We can save lot of time by using excel's autofill option to populate data by clinking the bottom right corner of cell and dragging it to any direction. Excel will populate any list of data (months , days , years , numbers) 

  - We can also add **custom list** to excel 

     **Adding Custom List For AutoFill**

  `file -> Options -> Advance -> Edit Custom List`

  Here We Can either add or import list (add manually here or write in current sheet and import list from there)

- Apply on Cell format (styles) to All The cell (row or column)

  - `Home -> Clipboard -> FormatPainter`

  ### Merge and Center 

  - Select the text and all empty cells you want to merge in and 
  - `Home -> Alignment -> Merge & Center` it will merge the text and center it 

## Doing Simple Math

We Are Familiar with old fashion sum formula to we skip it.

But One Important thing 

**We can find details about selected values cell or column by selecting them and look left bottom of sheet , there we can find values (sum , avg , min , max etc) of selected cells/columns or right click and get any value you want **

<u>We Can user `ctr + r` to fill the right column with same formula </u>

<u>We Can user `ctr + d` to fill the down column with same formula </u>

## Evaluate Formula 

As we know that order of execution of formula in excel just works as normal math order which is `BODMAS`

As we write complex formulas it is harder to think which part is executed first.

We can Evaluate the formula and debug it 

`Formula -> Formula Auditing -> Evaluate Formula`

## Rounding Functions 

### Round 

`=round(cellNumber, Digit how many you want)`

### Round Up

`=roundup(cellNumber, Digit how many you want)`

### Round Down

`=rounddown(cellNumber, Digit how many you want)`

### Building a complex formula or merging two formulas 

lets say we have a want to get average of numbers and same time we want to round those number 

**Get Average** `=B2/C3` and **Round it** `round(cell,digit)`

Now We Merge These two formulas Following `BODMAS` convention  in this way `=round((B2/C3),2)`

## Sorting Data

Apart from normal sorting we are aware of there is also custom sort

 `Home -> Editing -> filter & Sort -> custom sort`  

You can also access it by  `Data -> sort & filter`

Here we can add level (cells) we want to sort we delete level 

If the First column is header you can select `My data Has Headers` options to ignore that

## Soft Return || wrap Text

Key `alt + Enter`

Or

Select Cell You want to wrap text in `right clink -> formate cell -> alignment -> text control -> wrap text`

## Charts 

To insert chart 

- Select cell / column you want to insert char for 

  - you can select cell / column in parts by holding `alt` key

- `insert -> charts -> remoended charts(optional)`

- you copy chart in other sheet

   