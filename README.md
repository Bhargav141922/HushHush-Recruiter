Doodle, hushhush Recruiter
-- Project Structure and basic gist

Data Fetching and Preparation:
Fetch user profile links via API calls.
Perform web scraping on fetched data.
Convert and save data into a CSV file.
Store CSV data in an SQL Lite database.
Model Training and Testing:
Divide data from SQL Lite database into training, testing, and unseen data.
Train and test a model using the training and testing data.
Save trained model for each job role in a Pickle file.
Candidate Selection and Assessment Process:
Load trained model for each job role from Pickle file into 'selector.py'.
Process 'selected candidates' data using the model.
Manager selects candidates (Yes/No) through Manager Interface.
Manager-set requirements passed to HR Interface.
HR Interface generates list of eligible candidates.
Eligible candidates receive email for coding test.
Candidate Interface updates candidate status.
Candidates receive confirmation email and access to coding test.
Candidate Evaluation and Feedback:
Save candidates' coding test answers and Q&A in a database table.
Evaluate answers using OpenAI API.
Provide feedback based on coding test evaluation.
-- Initial Setup Procedure

Navigate to desired directory for project setup.
Clone project using: git clone https://github.com/Big-Data-Programming/bdp-oct23-exam-bdp_oct23_group13.git
Install requirements by running: pip install -r requirements.txt
Execute this command whenever requirements.txt changes.
-- Product Application Flow
