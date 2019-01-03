# Ad-Revenue-Optimization
Your Execution flow:

    Open the One day scheduler in Jupyter Notebooks.

    Rename the file containing your advertisements to the one on the pandas read line.

    Put it in the same folder as the dialy scheduler.

    Did I forget to tell you the format data is supposed to be in: [BookingNumber, BrandCode, ProgramCode, TapeCode, TapeDuration, ScheduleDate, SpotRate, StartTime, EndTime]

    Run every cell after that

    Startup is the function you gotta start with: Uncomment it in the last cell and follow remaining instructios to get the job done

    In addadv, if you want output into excel file use ExcelWriter just below the line where data enters the 'tempdf' dataframe. Remember you will be appending here.

    To export the program segments in between simply use ExcelWriter object just below the df_2 assignment. Remember you will be appending here
