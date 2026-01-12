##  End to end  machine learning project 


Why do we need a logger in ML projects?

Machine learning projects are long and complex. A logger helps you:

✅ Track model training progress
✅ Debug errors and crashes
✅ Monitor data preprocessing steps
✅ Record hyperparameters and metrics
✅ Maintain production-level code


What is utils.py?

utils.py is not a default Python file — it is created by developers to store:

Common helper functions

Repeated logic

Small reusable code blocks

Think of it as a toolbox 🧰 for your ML project.
<!-- -------------------------------------------------- -->
🔹 What is data_ingestion.py?

data_ingestion.py is a script/module that:

Fetches data from a source

Stores it in a standard location

Splits it (train/test)

Makes it ready for the next pipeline step

👉 It does NOT do heavy cleaning or feature engineering — only ingestion.

What is this code doing (big picture)

This code is for Data Ingestion in an ML project.

👉 Meaning:

Read raw data (stud.csv)

Save a copy as raw data

Split into train & test

Save them in artifacts/

Log everything

Handle errors properly