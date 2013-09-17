# A translation status webpage from a email archive

This project will consist of two parts:
- An email archive parser, which will be responsible for parsing the
email archive and submit information to the database
- A webpage that presents the information

## Email archive parser

* Fetch emails from since last execution and untill now.
* For each of these emails:
  * Parse the subject to determine the translation name and group
  * React on status changes in case of reservations or requests for proofreading
  * Parse commands and execute

The results of the processing of each of the emails shuld be gathered
in a string, that should be commited to log.