Software Carpentry summary
--------------------------

**Thursday**

1. Unix shell commands
	- where you are
	- looking at files: head, tail, cat
	- pipes
	- searching files: grep
	- for loops
	- scripts
	- history; repeating commands by number

2. Version Control: Git
	- initialise
	- working directory --> staging area --> repository
	- commits: should be logical chunks, so your commit message makes sense
	- viewing log
	- reverting mistakes
	- resetting

3. Databases: sqlite
	- several open options for database management
	- sqlite is small and simple
	- .schema
	- selecting data from a table, ordering data: note can filter on things you do not return
	- aggregation: count, max, min
	- importance of checking for NULLs and handling in a defined way
	- joining tables and selecting data
	- importance of defining your schema and which columns are comparable between tables

**Friday**

4. Python
	- iPython Notebook: cells can be code, or markdown, or plain text; can include LaTeX
	- Python is fast to read / write but comparatively slow to run: use for small simple jobs where optimisation is not necessary
	- classes: cannot add '2' and 3 (string v integer)
	- slices: accessing susbets of a string or list: half-open, 0-based
	- can save a notebook and relaunch later
	- can open data files within iPython Notebook

5. Version Control: Git
	- adding a remote repository
	- pushing to / pulling from a remote repository
	- cloning someone else's repository
	- merging and dealing with conflicts

**General**

6. General points made
	- 7 +/- 2 items in your working memory
	- cannot concentrate for longer than 45-90 mins - code in chunks that can be read in this time
	- get up, move, get blood flowing in between working
	- build up pipelines incrementally
	- the parson's test: read out your code
	- Reduce the gap between "I have the idea" and "I have the insight"
	- differencing tools: people build tools for the formats they use (e.g. not powerpoint, word)
	- the tool shapes the hand
	- remove redundancy to reduce mistakes
	- functions of functions
	- comprehension is greatest at intermediate levels of abstraction; your ability to handle abstractions will shift over time
	- the intangible things are always underfunded - no photo ops, names on buildings
	- instructors' course in Jan

7. Links and reading
	- http://test.development.rc.ucl.ac.uk/training/carpentry/git.html#/
	- Visual Quickstart: Unix and SQL
	- why Python is zero-indexed: https://plus.google.com/app/basic/stream/z13evl5h2xzuwb25w04cfph4co2xuf2a12s
	- Psychology of education: http://www.amazon.com/Flow-The-Psychology-Optimal-Experience/dp/0061339202, http://www.amazon.com/How-Learning-Works-Research-Based-Principles/dp/0470484101/
 	- organising projects: http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1000424, http://faculty.chicagobooth.edu/jesse.shapiro/research/CodeAndData.pdf, http://www.nber.org/econometrics_minicourse_2013/
 	- http://www2.smartbear.com/Best-Kept-Secrets-Code-Review.html

8. Things I wish had been covered:
	- git: gitignore, checkout (how does this differ from clone?)
	- testing
	- luckily there is info on these covered online!
