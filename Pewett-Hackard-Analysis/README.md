# Pewett-Hackard-Analysis

# Purpose
The point of this project is to find out the total amount of retiring employees based off their title and to see which employees can join a mentorship program. 

## Analysis

First, we need to get the employee number, first name, and last name from the employees table. Then, we need to get the employees title, from_date, and to_date from the titles table. After we gather all of this information, we need to join the tables together on the primary key, filter it to show birth date, and put the new information in a new table. 
Next, we make a unique_titles table. We do this by using the DISTICT ON statement to retrive the first occurrence of the employee number for each set of rows defined by the ON () clause. 
Lastly, we wrote a query to gather data from the dept_emp table and employees data and filtered it to show the employees that were born in 1965. This shows the employees that are eligible to participate in the mentorship program. 

# Results
- In the retirement_titles table, we can see all employees that are eligible to retire. We can also see how long they worked in each position. 
- In the unique_titles table, we can see the most recent title for employees of retirement age.
- The retiring_titles table shows most of the employees that are of retirement age have senior level titles. 
 ![retiring_titles](https://user-images.githubusercontent.com/80054925/116826128-1bfd7800-ab58-11eb-9054-12784c919205.png)
- The image below, which is the head of the mentorship_eligibilty csv, shows employees that are eligible to join a mentorship program. This image shows most of the employees have senior level titles. 
![mentorship_eligibilty](https://user-images.githubusercontent.com/80054925/116826180-5ff07d00-ab58-11eb-8832-a46aaf2cc4af.png)

# Conclusion

The results show that around 63 perent of the employees can retire or are eligible to join a mentorship program, so there will likely be a lot of positions that can be taken over. However, it is unlikely that there will be enough people to fuflill these jobs. I suggesst that companies pay attention to what those employees did that made them successful over the years and what allowed people to have a long lasting careers for the company.  
