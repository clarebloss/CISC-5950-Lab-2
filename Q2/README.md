# Question 2

Consider a Black vehicle parking illegally at street codes 34510, 10030, 34050. What is the probability that it will get a ticket (using a very rough prediction)?

Using the NYC Parking Data from 2022 (https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2023/pvqr-7yc4), the CSV file will be stripped of all data that does not contain a Vehicle Color name that is associated with the color black and that was not parked illegally at the specified street codes (34510, 10030, 34050). The K-Means algorithm is then run and the probability is calculated.

Starting from the Virtual Instance root, the parking data is stored in the path: /spark-examples/lab2 under the file name Parking_Violations.csv. The program and test.sh file is stored in the path: /spark-examples/lab2/Question2 under the file name streetCodesKmeans.py.
