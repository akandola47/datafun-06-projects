ARSHPREET KANDOLA
MODULE 6 
OCTOBER 1 2023

https://github.com/akandola47/datafun-06-projects

In this module, you will:

Perform a guided exploratory data analysis project.
Conduct a unique data analysis exploration.
The objective is to craft a compelling narrative ("tell a story") using data, showcasing not only your analytical skills but also your professional and engaging communication abilities.

Chapters
This module requires the skills learned in previous chapters. The first is a guided exploratory data project that focuses on diamonds.csv and is based on in Exercise 9.16 beginning on page 352 of the text. The second is a project of your choice, related to your domain.

Decide what you would like your second project to focus on / showcase. Review the requirements for the project and make sure your topic lends itself to successfully completing all requirements.

Task 1 - Prepare Your Module Repository
GitHub
Create a new repository named datafun-06-projects on GitHub.
Initialize it with the default README.md.
Local Machine
In VS Code, clone your new repo into your Documents folder.
Repository Essentials
Add a .gitignore file from a previous Python project.
Add a requirements.txt file to hold external dependencies for Jupyter notebooks and others as you need them. 
Update README.md
Modify the README.md to include your name, the link to your repo, and the focus of this project repository. 
Include instructions with the exact commands to: 
Create and activate your virtual environment.
Install all required external dependencies.
Execute your Python files.
Create your local virtual environment (hint: use venv to create a .venv folder)
Activate your local virtual environment (hint: call a command in the .venv subfolder)
Install any external dependencies you need (hint: use requirements.txt and all the files needed for Jupyter notebooks, pandas, etc.)
Push to GitHub 
Add and commit all your changes with a commit message "Initialized repo"
Push your changes to GitHub
 

Task 1 - Verify Repository
Take a screenshot of your GitHub project repository after you've pushed these changes to GitHub.
Display the screenshot as evidence of task completion.
Task 2 - Guided Diamonds Project
This first project is a guided exploration. 

Follow the instructions for Exercise 9.16 (starting pg. 350).
Complete the exercise in a Jupyter notebook. 
Include the title of the notebook, your name, and date at the top.
Include the following Markdown Section Headings in your notebook. 
Section 1-Load: Get the file, store it in your repo, and load it into a DataFrame. 
Section 2-View: Display the first 7 rows and the last 7 rows.
Section 3-Describe: Use the DataFrame describe() function to calculate basic descriptive statistics for all numeric columns. 
Section 4-Series: Use the Series method describe() to calculate the descriptive stats for all category/text columns.
Section 5-Unique: Use the Series method unique() to get unique category values. 
Section 6-Histograms: Use the DataFrame's hist() function to create a histogram for each numerical column.
 

Task 2 - Push to GitHub
Execute the completed notebook
Add, commit, and push your changes to GitHub. You can use incremental commits as you work - provide useful commit messages.
At the end, use a commit message like "Task 2 complete".
Verify your GitHub notebook appears complete and well-presented. 
 

Task 2 - Verify
Capture a screenshot of your completed notebook as viewed in GitHub at the conclusion of this task.
Display the screenshot as evidence of task completion.
 

Task 3 - Custom Exploratory Data Project
Use everything you've learned to conduct a unique data exploration project using some information related to your domain. 
Create a new notebook that uses a dataset of your choice.
The notebook name should make it clear this is your unique project.  
Use this project to feature all of the key skills learned. See the list above. 
Include challenging Python programming aspects - find a reason to use filter(), map(), and list comprehensions.
Have fun and make it unique.
Your second project must show the following Python skills and Markdown sections:

Section 1-Load - Read from a data file into a pandas DataFrame.
Section 2-View - Display the first 5 rows and the last 5 rows.
Section 3-Describe: Use the DataFrame describe() function to calculate basic descriptive statistics for all numeric columns. 
Section 4-Series: Use the Series method describe() to calculate the descriptive stats for all category/text columns.
Section 5-Unique: Use the Series method unique() to get unique category values. 
Section 6-Histograms: Use the DataFrame's hist() function to create a histogram for each numerical column.
Section 7-List: Get some of your information into a list. Process each item in the list (use for or comprehensions as you like). 
Section 8-Filter: Use filter() to show only part of the information. 
Section 9-Map: Use map() to transform some of the data. 
Include a title section with your name - this is your branding - make it professional and attractive.
Use Markdown section headings to professionally present your work. 
Tell a story with data - lead us through your project and summarize your interesting results. 
 

Task 3 - Push to GitHub
Execute the completed notebook
Add, commit, and push your changes to GitHub. You can use incremental commits as you work - provide useful commit messages.
At the end, use a commit message like "Task 3 complete".
Verify your GitHub notebook appears complete and well-presented. 
 

Task 3 - Verify
Capture a screenshot of your completed notebook as viewed in GitHub at the conclusion of this task.
Display the screenshot as evidence of task completion.
 

Optional Bonus Section
As part of your custom project, use a library or module we did not explore in class.
Consider imageio, nltk, texatistic, textblob, wordcloud, or others. 
Look for something new that might interest you. 
Learn it on your own and apply it to your domain/project. 
Clearly label your Section Bonus using Markdown. 
In the bonus section, explain what you chose, why, how it went, and your results. Do you recommend it? 
This is a chance to show advanced, creative skills - make it valuable for others by describing it well. 
 

Optional Bonus - Push to GitHub
Execute the completed notebook
Add, commit, and push your changes to GitHub. You can use incremental commits as you work - provide useful commit messages.
At the end, use a commit message like "Bonus complete".
Verify your GitHub notebook appears complete and well-presented. 
 

Optional Bonus - Verify
Capture a screenshot of your completed notebook as viewed in GitHub at the conclusion of this task.
Display the screenshot as evidence of task completion.

CREATING AND ACTIVATING A VIRTUAL ENVIORNMENT

Step 4: Set up a Virtual Environment Next, we'll create and activate a virtual environment specifically for this project. We'll also install additional packages required for this project.

Create a Virtual Environment Open the terminal in VS Code. (View / Terminal) Run the following command to create a virtual environment for this project. python -m venv .venv Verify that a new .venv folder was created. It may take a while for the command to complete.

🚀 Rocket Tip: When VS Code Python Extension offers to select the Environment, say Yes.

Activate the Virtual Environment Wait for the creation to finish, then activate the virtual environment:

For PowerShell: .venv\Scripts\Activate For macOS/Linux: source .venv/bin/ 🚀 Rocket Tip: Notice the terminal changes to reflect the active virtual environment.

INSTALLING DEPENDENCIES

Install Dependencies to the Active Virtual Environment Install additional project dependencies into the active virtual environment. The packages ipykernel and jupyterlab are required to run a notebook. The packages pandas, matplotlib, and seaborn are used to work with data and charts.

python -m pip install --upgrade pip ipykernel jupyterlab python -m pip install --upgrade pandas matplotlib seaborn python -m pip install --upgrade voila Alternatively, you can install all the packages listed in the requirements.txt file.

python -m pip install --upgrade -r requirements.txt Note: The --upgrade parameter gets the latest version of each package.

EXECUTING SCRIPTS IN PYTHON

With your repo folder open in VS Code, start exploring. Open, read, and run each project script (each file will have a .py extension) in order. You don't need to fully understand the code yet. Instead, try to figure out what each file is doing.

Open acquainted.py (or another .py file). Read the comments and code carefully. Execute each script - one at a time. On macOS/Linux, change python to python3 in the commands below. python acquainted.py python basic_expressions.py python basic_functions.py python circle_calc.py python data_io.py python easy_stats.py Helpful hint: Hit the up arrow in the terminal to get the last command. Edit as needed and hit return.