->A Python Flask web application that evaluates EAMCET response sheets automatically.
  Extracts both correct answers and student-selected responses using web scraping.
->Calculates section-wise marks for:
  * Mathematics
  * Physics
  * Chemistry
->Displays clean, user-friendly results through HTML templates.

->Features
 * Fetches response sheet from official EAMCET website
 * Uses BeautifulSoup to scrape correct answers
 * Extracts and compares student responses
 * Calculates total and subject-wise marks
 * User interface built using HTML + Flask templating Fast, accurate, and eliminates manual checking

->Tech Stack
 * Python
 * Flask
 * BeautifulSoup (bs4)
 * Requests
 * HTML / CSS

->User submits EAMCET response sheet URL.
 * App fetches page data using requests.
 * BeautifulSoup extracts: Correct answers (.rightAns),  Selected answers (.menu-tbl)
 * Answers are categorized into: Maths ,Physics ,Chemistry
 * Matching logic evaluates how many answers are correct.
 * Results are shown with subject-wise marks.
 
