# Excel-Skill-Building

Excel Skill Tracking Progress (Months 1-3)

Excell skills will be used as goal towards becoming a Data Analyst.

Day 1 - December 25th- PIVOT TABLES with AlexTheAnalyst https://drive.usercontent.google.com/download?id=1Ja022P6lkiXWE9iQJt2s940PCdgEHnUZ&export=download&authuser=0

Day 2 - December 26th- Excel Formulas: Max-min, IF/IFS with AlexTheAnalyst https://raw.githubusercontent.com/AlexTheAnalyst/Excel-Tutorial/refs/heads/main/Formula%20Excel%20Template.xlsx

Day 3 - December 27th- Excel Formulas continued: Len, Left-mid-right, Date to text, Trim, Concatenate, Sum/Sumif/Sumifs, Count/countif/countifs, Days, Network days, IF, Unique, Average If, Isblank, Vlookup, with AlexTheAnalyst 
https://raw.githubusercontent.com/AlexTheAnalyst/Excel-Tutorial/refs/heads/main/Formula%20Excel%20Template.xlsx

Day 4 - December 29- Xlookup in Excel: Multiple rows, Search order, Horizontal and Vlookup v. Xlookup with AlexTheAnalyst https://raw.githubusercontent.com/AlexTheAnalyst/Excel-Tutorial/refs/heads/main/XLOOKUP%20Excel%20Tutorial%20File.xlsx
      - Created a GitHub account
      - Conditional Formatting (Color schemes, define data quickly and pattern trends annd create new rules) With AlexTheAnalyst https://raw.githubusercontent.com/AlexTheAnalyst/Excel-Tutorial/refs/heads/main/Conditional%20Formatting%20Excel%20Tutorial%20File.xlsx
      
Day 5- December 30th- Charts in Excel- visual graphs, graph manipulation and customization

Day 6- December 31st- Cleaning Data in Excel- Finding format issues, grammar issues, duplicates.
      -To grammatically correct a column of data:
            -Insert new column
            -Select Cell block in corresponding row of column seeking to correct (E.G. D2 as a new column would align with the data in C2 to be corrected)
            -type =Upper or =lower or =proper in new column cell (D2 for example) followed by the column cell looking to be corrected (C2 for example)
            This should look something like: =Upper(c2) 
            Rename new column with original name with a '-fixed'
            
            IMPORTANT
            After data is cleaned in new column, copy and paste in original column with VALUES OPTION!!! This will paste as a string in the original unclean column and therefore you can delete the -fixed column. Now the original column is updated. 
                  -Shortcut to do this ^ would be: select beginning cell in -fixed column then CNTRL + Shift + down and then cntrl+C. Next click on the original first cell in the uncleaned column or just press the arrow left or right depending on original column                            position and right click to paste AS A VALUE. It should copy what was cleaned in the -fixed column. Now delete fixed column since this is a working document to be shared back. 
                  
      -When cleaning data, take stock of what is useful and what is not. Useful data would be data that you can visually represent, group and breakout with graphs or the like.
      -To Trim data would be useful when theres to many spaces between names or numbers out of error. Invisible spaces can cause issues later on when importing to SQL. 
            -Formula to Trim: Create new column alongside misformatted column.
            -Type =Trim(column cell to be fixed)
                  Example: =Trim(G2) and then enter.
                  
      -Currency needs to be cleaned in order to properly run in other programs like SQL to properly run calculations. you want to avoid special characters in numerical data (like the dollar sign $) so it doesnt turn back in SQL as a text or string that you cant work            with. 
            -To fix this and remove special characters, select the column to be cleaned and then choose Number under the home tab, then select general. 
            
      -The Dates in data sets need to be cleaned by being orgnaized and uniformed.
            To uniform the dates: Highlight the column to be fixed, then select the humber drop down in the Home tab. Select short date.
            
      
