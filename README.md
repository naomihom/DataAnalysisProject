# DataAnalysisProject
# Divorce Data Analysis

## Data Understanding
This dataset contains data about 170 people with their corresponding Divorce Predictors Scale (DPS) variables based on ***"Gottman couples therapy"***. The records were acquired from face-to-face interviews with people who were either already divorced or happily married. All responses were collected on a 5-point scale:
* 0 = Strongly Disagree  
* 1 = Disagree
* 2 = Neutral
* 3 = Agree  
* 4 = Strongly Agree

## Data Preparation
The questions from the interviews were originally numbered. To facilitate analysis, we renamed the columns with short versions of the questions:

* `Sorry_end`
* `Ignore_diff` 
* `begin_correct`
* `Contact`
* `Special_time`
* `No_home_time`
* `2_strangers`
* `enjoy_holiday`
* `enjoy_travel`
* `common_goals`
* `harmony`
* `freedom_value`
* `entertain`
* `people_goals`
* `dreams`
* `Love`
* `happy`
* `marriage`
* `roles`
* `trust`
* `likes`
* `care_sick`
* `fav_food`
* `stresses`
* `inner_world`
* `anxieties` 
* `current_stress`
* `hopes_wishes`
* `know_well`
* `friends_social`
* `Aggro_argue`
* `Always_never`
* `negative_personality`
* `offensive_expressions`
* `insult`
* `humiliate`
* `not_calm`
* `hate_subjects`
* `sudden_discussion`
* `idk_whats_going_on`
* `calm_breaks`
* `argue_then_leave`
* `silent_for_calm`

## Project Workflow
1. **Data Import and Initial Inspection:**
    * Data was imported from a CSV file hosted online.
    * Initial inspection of the data to understand its structure.
    
2. **Data Cleaning and Preparation:**
    * Column names were renamed for clarity.  
    * Handling of any missing or inconsistent data.
    
3. **Exploratory Data Analysis (EDA):**
    * Visualizations and statistical analysis to uncover patterns and insights.
    
4. **Modeling:** 
    * Decision Tree Classifier was used to predict divorce likelihood.
    * Performance metrics such as confusion matrix were used to evaluate the model.
    
5. **Conclusion:**
    * Summarizing findings and insights from the analysis.
    
## Dependencies
The following libraries were used in this project:
* `numpy`
* `pandas`  
* `seaborn`
* `matplotlib`
* `sklearn`

## How to Run the Project
1. Clone the repository:
    ```
    git clone <repository-url>
    ```
    
2. Navigate to the project directory:
    ```
    cd Divorce-Data-Analysis  
    ```
    
3. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
    
4. Run the Jupyter notebook:
    ```
    jupyter notebook Divorce\ Data\ Analysis.ipynb
    ```
    
## Files in the Repository
* `Divorce Data Analysis.ipynb`: Jupyter notebook containing the full analysis.
* `divorce_data1.csv`: The dataset used for training and testing.
* `new_divorce_test.csv`: Additional dataset for testing.

## Results
The project successfully identified key predictors of divorce using the provided dataset and a decision tree model. Detailed visualizations and metrics are provided in the Jupyter notebook.
