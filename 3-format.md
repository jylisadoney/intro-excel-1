---
title: Format Data
nav: true
---
Please download <a href="media/IntroExcel-Part1-SampleWorkbook.xlsx" target="_blank">`IntroExcel-Part1-SampleWorkbook.xlsx`</a> to follow along with workshop activities.

**Throughout this workshop `Click` refers to a `Left Click` with your mouse**

# Format and Sort Data

After we've organized our spreadsheet, we can work on formatting and sorting our data. 

We will discuss how to [format dates](#format-dates), [format currency](#format-currency), [sort data](#sort-data), and add [conditional formatting](#conditional-formatting).

## [Format dates](#format-dates)
In Excel, dates are easier to organize and sort when they are represented numerically.

Let's fix our `Hire Date` column to make it more readable.

* Navigate to the `Employee Sales sheet (or Sheet1)` in our workbook
* Click `Column E` to highlight it
* Navigate to the `Home` tab and the `Number` section
* Click the arrow in the bottom right of the `Number` section
* Under Category, click `Date`
* Scroll down and click `03/14/2012`
* Click `OK`

The dates in the `Hire Date` columns are now represented by numbers.

## [Format currency](#format-currency)
We can also format our `Sales Q1` and `Sales Q2` columns so that the data are displayed as Currency.
* Click `Column C`
* Drag to highlight `Column D` (both columns should now be highlighted)
* Navigate to the `Home` tab and the `Number` section
* Click the `drop-down` box
* Click `Currency`

The data in our `Sales Q1` and `Sales Q2` columns are now formatted as currency.

## [Sort data](#sort-data)
Now let’s say we want to organize our sheet based on `when an employee joined the company`.
* Highlight all of the data
  * Option 1: Click `Cell A1`, hold down the `Shift` key on your keyboard, and click `Cell E28`
  * Option 2: Click `Cell A1` and drag to highlight all data **OR**
  * Option 3: Hit `Ctrl + A` on your keyboard (`Cmd + A` for Mac users)
* Navigate to the `Data` tab and the `Sort & Filter` section
* Click `Sort`
* Check the `My data has headers` box
* In the `Sort by` drop-down box, click `Hire Date`
  * Set the `Sort on` drop-down box to `Values`
  * Set the `Order` drop-down box to `Oldest to Newest`
* Click `OK`

Now the data in our sheet are sorted based on Hire Date. We could also sort `Hire Date` as `Newest to Oldest`.

## [Conditional Formatting](#conditional-formatting)

`Conditional formatting` in Excel lets you:
* Format cells based on their values
* Format cells that contain certain information
* Format top or bottom values
* Format values that are above or below the average
* Format unique or duplicate values

### Add conditional formatting

Let’s say we want to highlight the `Sales Q1` amounts that are `equal or above the average`.
* Navigate to the `Employee Sales sheet (or Sheet1)` in our workbook.
* Click `Column C` to highlight the `Sales Q1 data`
* Navigate to the `Home` tab and the `Styles` section
* Click `Conditional Formatting`
* Click `New Rule`
* Click `Format only values that are above or below average`
* In the drop-down box, select `equal or above`

Now we have to set what we want the formatting to look like.
* Click `Format`
* Click `Fill`
* Click the color you want to use
* Click `OK`, then click `OK` again

We can now see that Excel has highlighted the `Sales Q1` amounts that are `equal or above the average` of our data.

### Edit conditional formatting
* Navigate to the `Home` tab and the `Styles` section
* Click `Conditional Formatting`
* Click `Manage Rules`
  * In the `Show formatting rules for` drop-down, select `This Worksheet`
* Click to highlight the rule you want to edit
* Click `Edit Rule` and enter your changes

### Remove conditional formatting

#### Specific cells
* Click and drag to highlight the cells(s) where you want to remove conditional formatting
* Navigate to the `Home` tab and the `Styles` section
* Click `Conditional Formatting`
* Click `Clear Rules` 
* Click `Clear Rules from Selected Cells`

#### Entire sheet
* Navigate to the `Home` tab and the `Styles` section
* Click `Conditional Formatting`
* Click `Clear Rules` 
* Click `Clear Rules from Entire Sheet`

## More Help

### Format data
To learn more about `formatting data`, open Excel and navigate to the `Home` tab and the `Numbers` section. 

You can also visit <a href="https://support.office.com/en-us/article/enter-and-format-data-fef13169-0a84-4b92-a5ab-d856b0d7c1f7?ui=en-US&rs=en-US&ad=US#ID0EAABAAA=Format_data" target="_blank">Microsoft's Enter and Format Data website</a>.

### Sort data
To learn more about `sorting data`, open Excel and navigate to the `Data` tab and the `Sort & Filter` section.

You can also visit <a href="https://support.office.com/en-us/article/import-and-analyze-data-ccd3c4a6-272f-4c97-afbb-d3f27407fcde?ui=en-US&rs=en-US&ad=US#ID0EAABAAA=Sort_and_filter" target="_blank">Microsoft's Import and Analyze Data website</a>.

### Add conditional formatting
To learn more about `conditional formatting`, open Excel and navigate to the `Home` tab and the `Styles` section. 

You can also visit <a href="https://support.office.com/en-us/article/Enter-and-format-data-fef13169-0a84-4b92-a5ab-d856b0d7c1f7#ID0EAABAAA=Conditional_formatting" target="_blank">Microsoft's Enter and Format Data website</a>.
