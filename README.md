# Gen Report (Python 3 Version)

## About Gen Report
Gen Report is a bash commandline application written in Bash script.  It generates a kind of "Client Report" based on mulitiple datapoints, it then allows the user to add any notes by hand before storing the entire thing inside of a Redis database as a string of text.

Each report is named based on the current date and the client name, and a user can display, edit, delete, or output a report to a file.

You can check out the original Gen Report app [here]("https://github.com/CodeCanna/GenReport")

I have decided to re-write this application because it's interface and flow is clunky and unintuitive.

## TODO For the Python3 version

* Port over the commands and basic functions of the original program in Python3
* Re-evaluate the report generation process
* I want tests written for this one for each method
* I want to bring OOP into the project
    * This will include re-writing functions
    * Refactoring a lot of the flow
