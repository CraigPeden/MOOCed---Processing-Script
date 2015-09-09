# MOOCed---Processing-Script
Script to automate the processing of Edinburgh MOOC data from raw Coursera into a database with extracts

Usage:

1. Firstly, emulate the file structure of the MOOC.ed server.

offline_process.py
env/
files/

2. Inside files place a folder for a course, named in the <course>-<iteration> format. E.g warhol-002

3. Run script

`python offline_process <course_name> <start_date>

e.g

`python offline_process warhol-002 2015-10-27

Course_name is <course>-<iteration>. Start date is Year-MM-DD

