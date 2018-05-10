# IHCodingTest
Submission for IH coding test results
Test Format:

Record the time you started and stopped
Try not to take more than 90 minutes (a few minutes extra is ok)
You may use internet resources, but no other collaboration is allowed
It is ok to skip questions you are unfamiliar with
Please use whatever language you are comfortable with for the coding questions
Feel free to edit your answer using your favorite IDE or online tool such as https://repl.it/

Start Time


End Time





1) Write a function that take and integer and returns a boolean of false when the integer is a prime number and true if it is not.  A prime number is a number greater than 1 that has no positive divisors other than 1 and itself.

Example:
isNotPrime(7) => false
isNotPrime(12) => true


<insert code here>




2) Given a string, find the last unique (non-repeating) character in it and return it's index. If it doesn't exist, return -1. 

Example:
lastUnique(“timedtestsarestressful”) => 21
lastUnique(“xabcabc”) => 0
lastUnique(“omnomnom”) => -1


<insert code here>




3) Write a function that given a path, will read in a file and print the number of occurrences of all words in the file that start with a vowel (‘a’, ‘e’, ‘i’, ‘o’, ‘u’). 

Example:
countVowelWords(“testfile.txt”) =>
30 a
14 and
17 in
24 of
5 end
2 under
...


<insert code here>




4) Using the API at http://www.openweathermap.com/current, write a function that takes a city name and returns the current temperature as an integer in Celsius.  For the API key you may use: 1cf173745177b0bbfc3f6cc7050bd8ab

Example:
getTemperature(“Atlanta”) => 26


<insert code here>




5) Given three tables (Patients, Hospitals, and Visits), write a SQL query that returns the total number of patients over 65 who visited each hospital in 2017. 

Patients
patient_id
name
date_of_birth
1
Alice
1965-04-02
2
Bob
1990-08-01
3
Charlie
1982-07-05

Hospitals
hospital_id
name
city
1
Emory
Decatur
2
Grady
Atlanta
3
Northside
Dunwoody

Visits
visit_id
patient_id
hospital_id
visit_date
1
2
2
2016-05-30
2
1
3
2016-08-04
3
3
3
2016-11-22
4
2
1
2017-01-15
5
1
2
2017-04-01

The result would look something like:

Hospital Name
Patients Over 65
Emory
125403
Grady
84537
Northside
163522


<insert SQL here>
