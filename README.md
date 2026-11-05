# MedicalDataCleaning
A dataset that contains various data records on medical insurance with over 1000+ individuals in the dataset. Information includes health related cost of insurance, individual age, region, BMI, and other represented fields that will be mentioned within the specifications of the dataset. 

## GOALS/SUMMARY
1. Dataset investigation
2. Cleaning and Transformation
3. Analysis
4. Robust Workflow

  -Inspect the raw dataset and document
  
  -Workflow clean and prepare the data analysis  
  
  -Formulate useful questions and answer them using the cleaned data. Such as Filtering, sorting, grouping, counting, calculating averages or totals, and etc.. . 
  
  -Include a script or workflow that can be rerun from the raw data
## SPECIFICATIONS ON DATASET
- Number of column: 7 ->  age, sex, bmi, children, smoker, region, and charges
- Number of rows: ~1339
- Potential errors: The cost of insurance within the dataset could be outdated since current rates could be different compared to. Although the dataset those   seem to get updated every year.
## SOURCE:
[https://www.kaggle.com/datasets/mosapabdelghany/medical-insurance-cost-dataset]

## STEP 1: Dataset Investigation :repeat:
team must inspect the raw dataset and document:
- File format and structur
- Number of records and fields
- Field names and apparent data types
- Missing or blank values
- Duplicate records
- Invalid or unexpected values
- Inconsistent spelling, capitalization, or formatting
- Outliers or suspicious values
- Problems with dates, numbers, delimiters, quoting, or encoding
- Any other issue that could affect the analysis

## STEP 2: Cleaning and Transformation :repeat:
- Removing or correcting invalid records
- Handling missing values
- Standardizing categorical values
- Converting dates or numeric fields
- Removing duplicates
- Filtering records that do not belong in the analysis
- Resolving inconsistent units or formats
- Creating derived fields
- Combining or aggregating records
- Separating invalid records for review rather than silently discarding them

  
Every important cleaning decision must be documented and justified. The report must explain what was changed,
why it was changed, and how the team verified the result.

## STEP 3: Analysis  :repeat:
must formulate useful questions and answer them using the cleaned data. The analysis should include
several operations, such as:
- Filtering
- Sorting
- Grouping
- Counting
- Summarizing
- Calculating totals, averages, rates, or percentages
- Comparing categories or time periods
- Identifying trends or unusual patterns
- Joining related data when appropriate

## STEP 4: Robust Workflow :repeat:
must include a script or workflow that can be rerun from the raw data. The workflow should:

- Be organized into logical steps
- Use meaningful filenames and directory structure
- Explain how to run it
- Check that required input files exist
- Validate important assumptions
- Detect malformed or unexpected data
- Report errors clearly
- Return an appropriate success or failure status
- Avoid silently hiding errors
- Preserve intermediate or diagnostic outputs when useful
- Produce the final cleaned data and analysis results automatically
- Be safe to run more than once
- Avoid hard-coded paths tied to one team member’s computer
