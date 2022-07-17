# Python Academy Project: Time Converter/Bootcamp Schedule(s)

## Project Brief 

Badmus Kwasi is a student of OneCampus enrolled in the Data Science Program. Badmus belongs to a cohort of over 800 students. During the first few bootcamps, Badmus observes the difficulty students in all the cohorts of OneCampus have in knowing their Bootcamp dates and times in their local/county time zones. This difficulty often results in students logging in too early, too late, or totally missing their bootcamps. Bootcamp times are always issued in Eastern Standard Time (EST) which is approximately UTC -5. This is the America_New York time. OneCampus has students in all the time zones of the world.

Badmus wants to develop a PYTHON-ONLY application that can be used to convert Bootcamp times from EST to any of the time zones requested by a student. The app should be able to convert the given date and time (Day and Time) to the requested time zone day and time.

The app should be able to store information about upcoming bootcamps by program type (Data Science, Machine Learning, and Data Analytics) using python containers ONLY and provide a corresponding list of the schedules in any time zone or country requested by a student. This app must not have any database implemented and should not read from nor save to any file on disk. All data MUST be stored in python code using containers ONLY.

As a bonus,if a student provides his/her full name, Country name and time zone, and email address, the app can generate an alert for the student on their computer (no need for an email script) notifying the student 24 hours before their next Bootcamp start time and 2 hours before Bootcamp Scedule (see attached excel sheet) Also provided are two lists of world time zone times.

## Project Specification
App Capability

1. App should hold information about the times in countries of the world (two lists have been provided. One contains 588 Countries times while the other has times for 404 countries).
- Should therefore be able to tell the current time in any country specified by the user by simply reading the current system time and time zone
2. App should hold the time zones and times of the 200 time zones provided.
- Should therefore be able to tell the time zone of any country specified by the user.
3. When provided the name of a source country and time zone, the app should be able to provide the equivalent time in any specified target country and display its time zone.
4. App should be able to generate the Bootcamp schedule in the time/timezone of any country specified.
5. As a bonus, the app should be able to read the current system time and alert the user if any upcoming Bootcamp is less than 24 hours from the current system time.
6. Additional bonus: Implement code with a database backend and a Graphical User Interface.

## Libraries Required
- datetime
- pandas

## Summary
In other to solve the difficulty students was facing with time conversion and bootcamp schedules, a functions is designed to handle this issue.

It has the following ability:

1. It has the ability to read the current system time of the user and convert it to any country specified by the user.
2. It has the ability to take time details about one Country (Source Country) and convert it to another Country time (Target Country).
3. It has the ability to show a single schedule based on the user given date and program. 
4. It can also diplay in a DataFrame format, all schedules associated with the user specified program. 

- This function gives room for converting the default time (EST) to another time based on the user specified country, in 3 and 4 above
