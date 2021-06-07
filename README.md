# LinkChecking
This python script checks a website for its links for their response codes. 
Links that are js are ignored ,for now. I'm still learning, so not sure its needed. 

- Run the script to get a text box into which you paste the web address of the site you'd like to test. 
- Run the function
- Returns a list of the link address, response code for that link. (is the title necessary? I may remove that.)
- Displays for readability in a pandas dataframe. 
- Uses groupby() method to show totals of each response code
- Will save out a .png of a bar chart of the response code totals. 

<br>
See the example, url.png. 

## for Jupyter notebooks
This file was made on a Jupyter notebook, but you are free to cutnpaste where ever you like to run it. 

## Goals
- [ ] refine to a .py file that can run from terminal <br>
- [ ] create a chrome extension to be used in conjunction with other accessibility checking tools, such as WAVE. 
- [ ] add timer so that it doesn't overwhelm websites (is this an issue?)

## Acknowledgements:
Many thanks to the people of the intertubes and places like StackExchange - where would I be without your help?
