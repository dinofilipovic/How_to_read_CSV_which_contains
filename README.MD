# UiPath forum problem
How to read CSV which contain ;

https://forum.uipath.com/t/how-to-read-csv-which-contain/247191

## Potential solution
This is a potential solution for reported problem.

## Solution explanation

There were some special characters in CSV document which needed to be replaced for Read CSV Activity to work:
1. Reading Text file (CSV)
2. Converting String (text) to List
3. Using Method RemoveRange
4. Storing data into string
5. Stroing string into csv
6. Read Range from CSV works now

## UiPath Code
Author: Dino Filipović