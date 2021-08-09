# Overview of the analysis
Determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program.

# Results
1. The first step was to obtain the number of employees eligible to retire:

![img](https://github.com/CarmenU18/Module-7-Challenge/blob/main/Resources/Number%20of%20Retiring%20Employees%20by%20Title.PNG)

2. Since the first query extracted all the number of employees that could retire without considering that we could have an employee with more than one record, an additional query was necessary to obtain the last record of each employee:

![img](https://github.com/CarmenU18/Module-7-Challenge/blob/main/Resources/Number%20of%20Retiring%20Employees%20by%20Title%20-%20no%20duplicates.PNG)

3. The next step was to identify in which area there is a higher risk of having a greater number of employees who are about to retire. For this purpose, the number of employees eligible for retirement by department was obtained:

![img](https://github.com/CarmenU18/Module-7-Challenge/blob/main/Resources/Number%20of%20Retiring%20Employees%20by%20Department.PNG)

4. The last step was to determine which employees were eligible to participate in the "Mentorship program".

![img](https://github.com/CarmenU18/Module-7-Challenge/blob/main/Resources/Employees%20Eligible%20for%20the%20Mentorship%20Program.PNG)

# Summary

1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?

    More than 90,000 positions will need to be filled once employees begin to retire.

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

    No, analysis of the data on employees eligible to participate in the mentoring program reveals that there are about 1,500 employees, this number seems insufficient, as the number of employees retiring is much higher. Furthermore, when we look at the breakdown of the numbers in terms of titles held by these employees, it is in the Senior positions where the gap is most evident.

    For example, for the position of Senior Engineer we have only 0.5% of employees who could fill the positions that would become vacant due to retirement.

    ![img](https://github.com/CarmenU18/Module-7-Challenge/blob/main/Resources/Mentorship%20vs%20Retiring%20Employees.PNG)
