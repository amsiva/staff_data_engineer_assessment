# staff_data_engineer_assessment

The following questions will be used to assess your ability to design, architect maintainable and scalable code.   Please fork this repo.

Submit everything needed to execute and validate your solutions for each of your answers.

Writing comprehesive tests are critical when submitting your solution.

<ol>1.  SQL</ol>

<ul>Write a stored procedure that accepts the following parameters:  first name, last name, date of birth, email and gender.  First, Last, email and one additional parameter are required to execute a match.  Return the id, decision( exact, possible, no match or unable to match) and score.  Be mindful of performance. Note: I'm looking for more than an exact match or not exact match in this solution.</br>

<ul>Note:  You must create your own Database and tables for this.  Please provide all scripts so that the evaluator can execute and validate your solutions.</ul></ul> 


<ol>2.  PySpark </ol>

<ul>Leveraging python (no direct SQL please) import the two csv files in the repo.</br>
		<ul>a. Create a staged version of the data</ul>
		<ul>b. Create a clinician mart</ul>
		<ul>c. Only store clinical titles </ul>
		<ul>d. Store only number after the "-"</ul>
		<ul>e. Create - Unique NPIs only</ul>
    <ul>f. Write tests.</ul>
</ul>
