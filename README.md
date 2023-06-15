# Work Day Scheduler Starter Code

## persudo code 

THEN the current day is displayed
at the top of the calendar
-- Get current date:
* Find JavaScript / JQuery function to provide current date
* Parse the date to something 'nicer' (months/day of week)

THEN I am presented with time blocks for standard business hours of 9am to 5pm
-- Provide a way to create multiple divs programatically
* Create a loop - loop should be hours 9-17
* Create divs from loop with elements in it.
* Create text elements that are easily accessible.

WHEN I view the time blocks for that day

THEN each time block is color-coded to indicate whether it is in the past, present, or future
-- Display proper colors (css) for past, present, and future
WHEN I click into a time block

THEN I can enter an event
-- Use textarea to input text
-- Add ID to textarea to make easily accessible.
WHEN I click the save button for that time block

THEN the text for that event is saved in local storage
-- Create save button with id = a save function that saves data
-- THEN save it via function to localstorage.

Adds:
-- One big object for time and slots
-- Loops 9..17
-- Functions to return:
    * AM/PM
    * CSS Class fot P/P/F
-- Function to save to localstorage
    * Why: It's called 3 times.