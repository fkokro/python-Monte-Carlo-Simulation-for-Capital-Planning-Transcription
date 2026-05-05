# python-Monte-Carlo-Simulation-for-Capital-Planning-Transcription
Example transcription of Capital Planning and budgeting Excel workbook to Python Jupyter Notebook

Monte Carlo Simulation - Capital Budgeting (Simple Example)

* Method for dealing with uncertainty.

	- Instead of using averages to determine values, we do numerous replications to produce a distribution.
	- When we are evaluation an investment project we usually assume the cash are known.
	- In reality, CFs can vary, causing NPV and IRR to vary.



Example Problem:
	
    Suppose a project costs $1 million and has average annual cash flows of $250,000/year with a standard deviation of $100,000. If the cost of capital is %15, evaluate the project.

	If CFs are normally distributed then
		- 68% of the time $150k to $350k
		- 95% of the time $50k to $450k
		- 99% of the time -$50 to $550k


Refer to the model development juypter notebook. We developed a model analyzing the above problem using NPV & IRR, then simulate this model using Monte Carlo simulation to evalute this problem further. 