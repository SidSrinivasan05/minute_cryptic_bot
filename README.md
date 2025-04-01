# minute_cryptic_bot

# Minute Cryptic Scraper & Solver

This Python project scrapes the **Minute Cryptic Puzzle** from the web and attempts to solve it using natural language processing and pattern matching techniques.

https://www.minutecryptic.com/

## Features
- **Scrapes the latest cryptic crossword clues** from the Minute Cryptic.
- **Parses and analyzes cryptic clue structures**, looks through the clues to see any hidden words, looks for synonyms of the first and last words
- **Attempts to solve clues** Attempts all of these submissions to try and solve the Minute Cryptic. Returns whether or not it could solve it

## How it works
- Uses selenium to scrape the Minute Cryptic and the length of the cryptic. Saves this information to a text file, along with the date
- If given an extra key word in the terminal, it will create a list of potential answers and using selenium, will see if it can find the answers
- Potential Answers are words within the clue itself that match the length of the cryptic, and synonyms of the first and last word of the clue (that also match the length)
- Prints out whether it solved it or not. Saved this to a csv file.
- Can access its success rate (~33.33%)

## Modules
- Selenium
- BeautifulSoup
- Requests
- Sys
- Pandas

## Background
This was a fun side project made mostly as a joke. 
