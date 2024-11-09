# README

## AUTHOR CONTACT INFORMATION
Please go to [cobwebscripts.com](http://cobwebscripts.com) to find up to date social media links to contact me.

## WHAT IS IN THIS REPOSITORY
- Yahoo Finance Power Query.xlsx
  - The actual Excel file you can use right away. Follow the [steps listed](#how-to-use-this-file) to start generating queries.
- Yahoo Finance Power Query Script.txt
  - The text of the Power Query script used. This can be accessed within the Excel file as well.

## HOW TO USE THIS FILE
0. Have a version of Excel have has Power Query.
1. [Download Yahoo Finance Power Query.xlsx.](https://github.com/cobwebscripts/yahoo-finance-excel-power-query/raw/04c5dee020cc93d71d7cea7f31527d1d45dbdcad/Yahoo%20Finance%20Power%20Query.xlsx)
2. Open Yahoo Finance Power Query.xlsx.
3. If you see the Security Warning asking for permission to enable External Content, click and allow it. You need this to be able to query Yahoo Finance.
![Screenshot showing the Security Warning asking for permission to enable External Content.](https://github.com/user-attachments/assets/71350249-5c30-4571-9441-9450dbb2e8f6)
4. To open the Data panel, click the Data tab (labeled 1) and then the Queries & Connections button (labeled 2). 
![Screenshot showing Data tab and the Queries & Connections button.](https://github.com/user-attachments/assets/c7b65c22-5cfb-4bc0-acf9-a5ec24725815)
5. Double click the Stock Data Generator Query, or right click > Invoke.
![Screenshot showing the Stock Data Generator Query.](https://github.com/user-attachments/assets/46a5edec-201d-4e52-92d7-8166a82de231)
6. Fill out the Parameters. 
   - For Resolution choose one of the following options corresponding to 1 day, 1 week, and 1 month, respectively:
     - 1d
     - 1wk
     - 1mo
   - For Ticker, enter the desired ticker in Yahoo Finance format. For example for Apple, enter AAPL.
![Screenshot showing the Parameters box.](https://github.com/user-attachments/assets/8dbd6332-17f8-479a-9c99-af989970fd20)
7. Click the Close & Load button to have the data saved to the sheet.
![Screenshot showing the Close & Load button.](https://github.com/user-attachments/assets/e100ba15-f84a-4121-98cc-adde646cec3b)
8. Enjoy analyzing the data!
![Screenshot of the end result.](https://github.com/user-attachments/assets/ace28e14-f7f9-4e19-86f4-fcbfd502828f)

## TODO
- Transform Timestamps to be YYYY-MM-DD instead
