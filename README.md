Folder update content:
Update date：July 25, 2020

URL:https://miosagawa.github.io/01_Work-Day-Scheduler/Assets/index.html
Github:https://github.com/miosagawa/01_Work-Day-Scheduler


1.Schedule creation（Created according to the following conditions）

    GIVEN I am using a daily planner to create a schedule
    WHEN I open the planner
    THEN the current day is displayed at the top of the calendar
    WHEN I scroll down
    THEN I am presented with timeblocks for standard business hours
    WHEN I view the timeblocks for that day
    THEN each timeblock is color coded to indicate whether it is in the past, present, or future
    WHEN I click into a timeblock
    THEN I can enter an event
    WHEN I click the save button for that timeblock
    THEN the text for that event is saved in local storage
    WHEN I refresh the page
    THEN the saved events persist


※Supplementary explanation:
    Some of the following contents could not be reproduced. 
    ”Each time block is color coded to indicate past, present, or future”