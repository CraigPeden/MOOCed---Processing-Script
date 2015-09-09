# MOOCed - Processing-Script
Script to automate the processing of Edinburgh MOOC data from raw Coursera into a database with extracts

Usage:

1. Create Virtualenv then Install Dependences

  `virtualenv env`

  `source env/bin/activate`

  `pip install -r requirements.txt`

2. Emulate the file structure of the MOOC.ed server. Top level folder should be:

  offline_process.py
  
  env/
  
  files/
  
  requirements.txt

3. Inside files/ place a folder for a course, named in the course-iteration format. E.g warhol-002

4. Run script from within the top level folder containing the script. NOT /files.

  `python offline_process.py <course_name> <start_date>`

  e.g

  `python offline_process.py warhol-002 2015-10-27`

  Course_name is course-iteration. Start date is Year-MM-DD

