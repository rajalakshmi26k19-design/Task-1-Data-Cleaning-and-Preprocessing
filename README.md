# Task-1-Data-Cleaning-and-Preprocessing
1) Identify and handle missing values using filters in Excel:-
-> Select the column with missing values, then use Data > Filter. Click on the filter arrow for the column, select Blanks to see rows with missing values.
-> Replacing missing data with a constant,  Highlight the range, then press Ctrl + H to open Find and Replace. Leave Find what blank, enter 0 in Replace with, and click Replace All.
2) Remove duplicate rows using Excel’s “Remove Duplicates” -> selct data > click remove Duplicates.
3) Standardize text values > I have created CONTACT Name using CONTACTLASTNAME & CONTACTFIRSTNAME
4) Convert date formats to a consistent type (e.g., dd-mm-yyyy) > To convert date formats in Excel to a consistent dd-mm-yyyy type, use the "Format Cells" dialog box by selecting the cells, pressing Ctrl+1, choosing "Custom" under the "Number" tab, and entering dd-mm-yyyy in the "Type" box.  
5) Rename column headers to be clean and uniform (e.g., lowercase, no spaces) > use a formula LOWER(SUBSTITUTE(A1," ","")) to convert the header in cell A1 to lowercase and remove spaces.    
6)Check and fix data types (e.g., age should be int, date as datetime).
Select the cells: containing the data you want to check or format.
Right-click: on the selected cells and choose "Format Cells..." (or press Ctrl + 1).
In the "Format Cells" dialog box, navigate to the "Number" tab. 
Category:
For age (integers), select "Number" and set "Decimal places" to 0.
For dates, select "Date" and choose the desired date format from the "Type" list.
For times, select "Time" and choose the desired time format.
Click "OK".
