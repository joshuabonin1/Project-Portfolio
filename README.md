The purpose of this project was to collect data and calculate process completion percentage for key warehouse processes. 
I was given the times that these processes should be completed by, with the requirement that the percentage column to be color filled based on status.
Green: 
  = 100% completion, regardless of time
Yellow: 
  < 100% completion and current time < (deadline time - 2 hours)
  between 80% and 100% completion and current time > (deadline time - 2 hours) 
Red: 
  < 80% completion and current time >= (deadline time - 2 hours)
  < 100% completion and current time > deadline time
I utilized many Common Table Expressions (CTEs) to gather the data for each process.
I unioned the rows for each process, utilizing a group by at the end for the common dates.
See JPG file of the output dashboard.
