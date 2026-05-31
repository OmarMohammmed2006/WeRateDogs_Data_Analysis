# WeRateDogs Data Analysis 🐕

A comprehensive data analysis and visualization project analyzing tweets from the popular [@WeRateDogs](https://twitter.com/dog_rates) Twitter account.

## Project Overview

This project performs exploratory data analysis (EDA) on Twitter data from the WeRateDogs account, which is known for humorously rating dogs on a scale and providing witty commentary about dog photos. The analysis includes data gathering, assessment, cleaning, and detailed visualizations to uncover insights about the tweets, ratings, and engagement metrics.

## Dataset

The project utilizes three main data sources:

1. **Twitter Archive Data** (`twitter-archive-enhanced.csv`)
   - Contains tweet information from the WeRateDogs account
   - Includes tweet text, timestamps, retweets, and favorites
   - Contains dog rating numerators and denominators

2. **Image Predictions Data** (`image-predictions.tsv`)
   - Neural network predictions on dog images in tweets
   - Contains confidence scores for predicted dog breeds
   - Includes whether prediction is actually a dog

3. **Twitter API Data** (`tweet-json.txt`)
   - Additional tweet metrics from Twitter API
   - Includes retweet counts, favorite counts, and timestamps
   - Provides rich engagement data for analysis

## Project Structure

```
WeRateDogs_Data_Analysis/
├── README.md
├── Final Project/
│   ├── Data/
│   │   ├── image-predictions.tsv
│   │   ├── tweet-json.txt
│   │   └── twitter-archive-enhanced.csv
│   └── Report/
│       └── Data Analysis (WeRateDogs).ipynb
```

## Methodology

### 1. **Data Gathering**
   - Downloaded archive data from the provided CSV
   - Queried Twitter API for additional metrics
   - Retrieved image predictions from pre-trained neural network

### 2. **Data Assessment**
   - Identified missing values and data quality issues
   - Assessed data types and formats
   - Detected duplicates and inconsistencies

### 3. **Data Cleaning**
   - Handled missing values appropriately
   - Standardized data types and formats
   - Resolved data quality issues
   - Merged datasets from multiple sources

### 4. **Exploratory Data Analysis**
   - Analyzed rating distribution and trends
   - Examined dog breed predictions
   - Studied engagement metrics (retweets, likes)
   - Investigated temporal patterns

### 5. **Visualization & Insights**
   - Created visualizations to illustrate key findings
   - Generated summary statistics
   - Provided actionable insights

## Key Findings

The analysis explores:
- **Rating Patterns**: Distribution and trends in how dogs are rated
- **Popular Breeds**: Most commonly predicted dog breeds in tweets
- **Engagement Metrics**: Relationship between content and social media engagement
- **Temporal Trends**: How the account's activity has evolved over time
- **Tweet Characteristics**: Analysis of tweet text, dog stages, and naming patterns

## Technologies Used

- **Python 3**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Jupyter Notebook**: Interactive analysis environment

## How to Use

1. Navigate to the `Final Project/Report/` directory
2. Open `Data Analysis (WeRateDogs).ipynb` in Jupyter Notebook
3. Run all cells to execute the analysis
4. Review visualizations and insights generated throughout the notebook

## Installation

To reproduce this analysis:

```bash
# Clone the repository
git clone https://github.com/OmarMohammmed2006/WeRateDogs_Data_Analysis.git
cd WeRateDogs_Data_Analysis

# Install required packages
pip install pandas numpy matplotlib seaborn jupyter

# Launch Jupyter Notebook
jupyter notebook
```

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

## Data Notes

- Tweet timestamps are from August 2015 through August 2017
- The dataset contains over 2,000 tweets with associated metadata
- Dog ratings use a humorous scale (e.g., 14/10, 11/10) rather than traditional 10/10 scoring

## Author

**Omar Mohammed**  
GitHub: [@OmarMohammmed2006](https://github.com/OmarMohammmed2006)

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Data sourced from the [@WeRateDogs](https://twitter.com/dog_rates) Twitter account
- Analysis performed as part of data science coursework
- Inspired by the humorous and heartwarming nature of WeRateDogs

---

**Note**: This project demonstrates proficiency in data wrangling, cleaning, analysis, and visualization using Python and Jupyter Notebooks.
