## My pagedown rendered CV

This CV has been made with the help of the code from Nick Strayer: 
https://livefreeordichotomize.com/2019/09/04/building_a_data_driven_cv_with_r/


## Structure

The main files are:

- `index.Rmd`: Source template for the cv. 
- `index.html`: The final output of the template in html. 
- `cv.pdf`: The final output of the template in pdf.
- `parsing_functions.R`: A series of small functions for parsing a position entry into the proper HTML format. 
- `gather_data.R`: Loads the data that makes up the body of both the CV and resume. In my case I only pull the data from a public google spreadsheet.
- `css/`: Directory containing the custom CSS files used to tweak the format from pagedown. 


