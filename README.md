# JeopardyPowerPointWithMacros

This is a PowerPoint template and all associated files to run custom Jeopardy! style games.

- First, install the two font files, ITC Korina Bold and Swiss 911.
- Next, open JeopardyTemplate.pptm in PowerPoint (you may wish to save the PowerPoint as a new file to preserve the template).
- If you encounter issues with the macros not being found or not allowed to run on your system, copy and paste them from macros.txt into your PowerPoint VBA editor.
- Next, write your clues and answers in questions.csv.
- Each column of the CSV corresponds to one of the six categories.
- The first row of the CSV is the category names. 
- The next five rows are the clues.
- The last five rows are the answers.
- Once you have added and saved your data in questions.csv, move the CSV to the same directory as the PowerPoint.
- Then run the LoadJeopardyFromCSV macros from the developer tab.
- Your game should be ready to play now; just press present.
