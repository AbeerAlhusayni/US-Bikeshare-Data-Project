### Date created
14th Feb'21

### Project Title
# Explore-US-Bikeshare-Data Project


### Description
In this project, Python is used to import US bike share data and answer interesting questions about it by computing descriptive statistics for three major cities in the United States — Chicago, New York City, and Washington.
- The source code takes in raw input from the user to create an interactive experience.
- According to the input the code will import the data and will provide information by computing descriptive statistics.

### Files used
bikeshare_2.py


### Credits
* YAQEEN AL MAHDI (Udacity instructor)

### Software
* _Python 3, NumPy,_ and _Pandas_ installed using _Anaconda_
* A text editor.
* A terminal application (_Terminal_ on _Mac_ and _Linux_ or _Cygwin_ on _Windows_).


## Code explained in Detail:
### How the program works:
The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions will change! There are four questions that will change the answers:

* Would you like to see data for Chicago, New York, or Washington?
* Would you like to filter the data by month, day, or not at all?
* (If they chose month) Which month - January, February, March, April, May, or June?
* (If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?

The answers to the questions above will determine the city and timeframe on which you'll do data analysis. After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit.

### The Datasets
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

* Start Time (e.g., 2017-01-01 00:07:57)
* End Time (e.g., 2017-01-01 00:20:53)
* Trip Duration (in seconds - e.g., 776)
* Start Station (e.g., Broadway & Barry Ave)
* End Station (e.g., Sedgwick St & North Ave)
* User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:

* Gender
* Birth Year

### Statistics Computed
The code helps user to tell about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, the code output will provide the following information:

* 1 Popular times of travel (i.e., occurs most often in the start time)

  - most common month
  - most common day of week
  - most common hour of day

* 2 Popular stations and trip

  - most common start station
  - most common end station
  - most common trip from start to end (i.e., most frequent combination of start station and end station)

* 3 Trip duration

  - total travel time
  - average travel time

* 4 User info

  - counts of each user type
  - counts of each gender (only available for NYC and Chicago)
  - earliest, most recent, most common year of birth (only available for NYC and Chicago)
