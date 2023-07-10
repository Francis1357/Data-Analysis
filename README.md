# The Student data Dashboord
The student data is used to determine the number of student admitted at a particular year, and their expected year of graduation, showing their field of studies and their areas of specializtion. The data was sourced from kaggle dataset and was imported into power BI for cleaning, transformation and visualiztion.

# Question to be answered
1. which field of study and specializtion has the highest number of students?
2. which year has the highest number of Admission?
3. what is the total sum of discount on fee and the highest amount of discount by year?
4. what is the total sum of actual fee and highest amount by year?
5. which specializtion has the highest discount recorded and which year?

   # Cleaning of data
   1. The header was assigned to their datatypes
   2. Another column was created and named "Actual fee" this is gotten from substraction of Fee from the Discount on fee.
   3. currency value was assigned to the fee columns paid by each student.
   4. The expected year of graduation column was arranged to help sort out the disorderliness of year of admission by the student. this means that some year of admission are earlier than the expected year of graduation. ( e.g year of admission : 2022, expected year of graduation: 2018)
       2022 year of admission was replaced with 2019
       2021 year of admission was replaced with 2018
       2020 year of admission was replaced with 2017
       2019 & 2018 year of admission was replaced with 2016
      
# Answer to the Question
1. ELEctrical Engineering , Web development
2. 2016
3. $2.5bn, 2021
4. $22,52bn, 2020
5. Machine learning

# Conclusion
From the analysis, Machine learning has the second highest number of student in fied of study by specialization with the highest discount fee recorded as of year 2018, but in  year 2023, Artificial intelligence has the highest discount fee recorded that year with respect to its specialization. there is no much discrepancy with the number of the students in each field and in specialization.

