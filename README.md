# datafun-04-eda

## How to Install and Run the Project

### Project Intialization
1. Fork an existing repo or create a repo in GitHub
2. Clone repo to local environment
3. Add .gitignore and requirements.txt files
4. Use Git to add, commit, and push new files to GitHub
5. Create a local virtual environment for project
6. Install dependencies

### Project Workflow

##### Step 1. Initial Title, Header and Imports
1. Create a Markdown title
2. Add a Markdown header with author name, purpose and date at the top
3. Create a Markdown cell numbered section to list imports
4. Create a Python cell for all the import statements need for the notebook

#### Step 2. Load Data

#### Step 3: Initial Data Exploration
- Get familiar with the dataset's format, size, and column details using the head(), shape(), types(), and info() functions

#### Step 4: Initial Descriptive Statistics
- Use DataFrame describe() method to obtain a statistical summary of the numerical columns

#### Step 5: Initial Data Distribution for Numerical Columns
- We can show a histogram for a single numerical column by providing the exact column name
- **Ex:**
```python
# Inspect histogram by one numerical column
iris_df['sepal_length'].hist()
```
- To show histograms for ALL numerical columns, we can use hist()
- **Ex:**
```python
# Inspect histograms for ALL numerical columns
iris_df.hist()
```
#### Step 6: Initial Data Transformation and Feature Engineering
- This phase of the data preparation or preprocessing is a multifaceted process that involves both cleaning and transforming the data for analysis
- This step refines raw data into a form where additional analytical techniques can be applied more effectively 

#### Step 7: Initial Visualizations
- Once the data is structured, the next step is to create visualizations that highlight important patterns and relationships. Using appropriate chart types helps reveal insights effectively.
- Libraries like Seaborn and Matplotlib offer a wide range of visualization options

#### Step 8: Initial Insights
- Add a section that summarizes your initial insights based on the facts discovered during the initial exploratory data analysis