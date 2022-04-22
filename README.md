# Exploratory Data Analysis - Bike Sharing Rental
Three months ago (**August, 2020**), I decided to start Hacktiv8’s Introduction To Python For Data Science Class Program and I’ve learned a lot since then. This course includes all the materials you need to become a Data Scientist. At the end of the program, each student is required to complete a Data Analysis or Machine Learning Project. The project I’m working on is “Data Analysis of Bike Sharing Rental”, which I basically worked on by answering a few questions below to get insights from the data.

# Outline
The bike sharing rental dataset has a total of 46,230 rows x 16 columns. Where this dataset describes the bike sharing system which is a means of renting bicycles starting from getting a membership, renting, borrowing and returning bicycles. Business processes are carried out automatically through a network of kiosk locations throughout the city. Using this system, people can rent bicycles from one location and return them to another as needed.

<p align="center">
  <img width="400" height="600" src="https://miro.medium.com/max/1400/0*UZRkrOwVjPJ2V84o">
</p>

There are several questions I asked myself about the data, and these are five questions that I am going to answer in this article:
1. Which age group uses the Citybike rental the most and also what gender?
2. How many trips (borrowed bicycles) are there every Monday — Sunday and the hour?
3. What days have the most bicycle borrowings occurred?
4. 5 Favorite station of departure and time (hour) with your most favorite bike rental?
5. Does the age of a person affect the trip duration by the minute?

## Built With
The following are details of the programming language and libraries used in building this project: <br>
- [**pandas**](https://pandas.pydata.org/)<br>
- [**NumPy**](https://numpy.org/)<br>
- [**seaborn**](https://seaborn.pydata.org/)<br>
- [**matplotlib**](https://matplotlib.org/)<br>

## Process
1. Step 1: Define problem statement / data requirements specification.
2. Step 2: Data collection (including SQL connectivity using python).
3. Step 3: Data cleansing
4. Step 4: Data preprocessing
5. Step 5: Data analysis
6. Step 6: Data communication (visualize and share the results)

## Conclusion
These are the summary of what I have done.
- The age group that uses the city bike rental the most is Gen X with an age range of 40–55 years. And the gender that uses the Citybike rental the most is men.
- The highest total daily borrowing of bicycles is Thursday with a total of 3,076 transactions and the most daily borrowing times today are 08 AM, 04 PM, and 06 PM. Then in second place for the most total daily bicycle borrowings is Friday with a total of 950 transactions and the most daily borrowing time today is 08 AM. Finally, for the most daily total borrowed bicycles, the next is Tuesday with a total of 924 transactions and the most daily borrowing time today is 08 AM.
- The day that has the most bicycles borrowed is Thursday with a total of 8,470 transactions.
- The 5 favorite departure stations for borrowing bicycles and favorite times are:<br>
i.) Grove St PATH with favorite times for borrowing bicycles is 05 AM, 06 AM, 07 PM and 08 PM.<br>
ii.) Hamilton Park with favorite time to rent bicycles is 08 AM.<br>
iii.) Columbus Dr at Exchange P1 with favorite time to rent a bike is 5 PM.<br>
iv.) Sip Ave with favorite time to borrow bicycles is 06 PM.<br>
v.) Newport PATH favorite time to rent bikes is 05 PM.<br>
- The user’s age does not affect the duration of the bicycle borrowing (trip duration by the minute), and vice versa. Because the results of the visualization above do not show a pattern of relationship between User Age and Borrowing Time. Although the Mean Absolute Error (MAE) value obtained from the model made is 4 minutes from the time value of the original data.

## Additional Note
Please read the following link for further information about this project's documentation:<br>
[**Data Analysis of Bike Sharing Rental using Python**](https://yandaafrida.medium.com/data-analysis-of-bike-sharing-rental-using-python-8c3f20c8208f)
