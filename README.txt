1. Authors:
Yasmin Harebin 
Anaiya Meikle
Anaya Mackle 

2. FIle/ Folder Overview: 
/notebooks – Jupyter Notebooks and CSV files 
README.txt – Instructions for running and reproducing the project

3. How to Run the Project 

4.1 Setup
Unzip the project folder 
Open Jupyter Notebook.
Upload all files into Jupyter Notebook: 
1. total_domestic_box_office.csv
2. top_grossing_movies.csv
3. top_gross_cleaned.ipynb
4. movie_months.csv
5. highest_grossing_movies_data.ipynb
6. calculated_predictability_bias.ipynb
7. box_office_summary.csv
8. Oscar_information_3.ipynb
9. Oscar_information.csv
10. MaxWeeksScraper.ipynb
11. MaxWeekVisuals.ipynb
12. FirstMonthVisuals.ipynb
13. FirstMonthScraper.ipynb
14. DomesticBoxOfficeScrapper.ipynb
All files must be in the same folder in order to run.


4.2 Important Note
Do not run the following notebooks containing API calls and webscraping 
1. Oscar_information_3.ipynb
2. Highest_grossing_movies_data.ipynb
3. MaxWeeksScraper.ipynb
4. DomesticBoxOfficeScrapper.ipynb
5. FirstMonthScraper.ipynb
The generated CSV files with the raw data are already generated and saved for use by the analysis notebooks. We had to manually input parts of the data in the csv files as webscraping could not collect all pieces. 

4.3 Run Order and Instructions 
File 1: top_gross_cleaned.ipynb
	Cell 1: Import and Load CSVs
	Cell 2: Define Cleaning Function 
	Cell 3: Find columns and clean values 
	Cell 4: Generates/Saves Cleaned CSV
Note: After running the notebook, a new CSV file titled top_grossing_movies_with_gross_clean.csv will be saved. 
FIle 2: calculated_predictability_bias.ipynb 
	Cell 1: Import and Load CSV Files 
	Cell 2: Define Cleaning Function
	Cell 3: Appy Title Cleaning 
	Cell 4: Prepare Oscar Nomination Columns
	Cell 5: Merge Essential Components of Datasets 
	Cell 6: Compute Correlations
	Cell 7: Visualizations 
File 3:  MaxWeekVisuals.ipynb
	Cell 1: Import modules
	Cell 2: Import box_office_summary.csv
	Cell 3: Get rid of outlier weeks in box_office_summary.csv
	Cell 4: Visualization for both Past and Current Era
	Cell 5: Visualization for Past Era only 
	Cell 6: Collecting Past Era week numbers
	Cell 7: Printing statistics
	Cell 8: Redefining statistics 
	Cell 9: Rounding and stating statistics. 
	Cell 10: Visualization for Current Era only 
	Cell 11: Collecting Current Era week numbers
	Cell 12: Printing statistics
	Cell 13: Redefining statistics
	Cell 14: Rounding and stating statistics. 
File 4: FirstMonthVisuals.ipynb
	Cell 1: Import modules
	Cell 2: Import movie_months.csv 
	Cell 3: Visualization for both Past and Current Era
	Cell 4: Separating the csv file data into the Past and Current Era
	Cell 5: Visualization for the Past era
	Cell 6: Visualization for the Current Era
