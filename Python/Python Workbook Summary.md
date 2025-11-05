\# Python Workbook Summary

This workbook serves as an organised manual for honing fundamental
Python programming and data handling abilities. It consists of four days
of practical exercises and projects with an emphasis on real-world
applications such as Pandas data analysis, manipulation, and
visualisation.

\## Day 1: Theory

\### Origins of Python - Developed by Guido van Rossum at CWI in the
late 1980s - Official release in 1991 - Designed to be simple,
accessible, and enjoyable - Named after \*Monty Python\'s Flying
Circus\*

\### General Uses - Web development (Flask, Django) - Scripting and
automation - Machine learning and data science - Scientific computing -
Software development and testing

\### Python in Data Analysis - \*\*Pandas\*\*: data manipulation -
\*\*NumPy\*\*: numerical operations - \*\*Matplotlib/Seaborn\*\*:
visualisation - Used for EDA, reporting, automation, and handling large
datasets

\## Day 2: FizzBuzz Programming Task - Loop from 1 to 100 - Print:  -
\`\"fizz\"\` for multiples of 3  - \`\"buzz\"\` for multiples of 5  -
\`\"fizzbuzz\"\` for multiples of both  - Else, print the number

\## Day 3: Pandas Data Analysis -- \`student.csv\`

\### Exercise 1: Loading and Exploring - \`pd.read_csv()\`, \`.head()\`,
\`.info()\`, \`.describe()\`

\### Exercise 2: Indexing and Slicing - Select columns: \`name\`,
\`mark\` - Slice rows: \`.iloc\`, condition \`class == \'Four\'\`

\### Exercise 3: Data Manipulation - Add \`passed\` column - Rename
\`mark\` to \`score\` - Drop \`passed\` column

\### Exercise 4: Aggregation and Grouping - Group by \`class\`, compute
mean - Count students per class - Average mark by \`gender\`

\### Exercise 5: Advanced Operations - Pivot table: \`class\` vs
\`gender\` with \`mark\` - Add \`grade\` column:  - A: ≥85, B: 70--84,
C: 60--69, D: \<60 - Sort by \`mark\` descending

\### Exercise 6: Exporting Data - Save DataFrame with \`.to_csv()\`

\### Exercise 7: Visualisation (Optional) - Use Matplotlib/Seaborn for:
 - Grade distributions  - Class performance  - Gender comparisons

\## Day 4: GDP Data Exploration -- \`GDP (nominal) per Capita.csv\`

\### Task 1: Initial Exploration - Load data into \`df\` - Display first
10 and last 5 rows - Select \`Country/Territory\`, \`UN_Region\`

\### Task 2: Group Activity - Use \`Day_4_Python_Activity.ipynb\` -
Freestyle exploration with additional datasets
