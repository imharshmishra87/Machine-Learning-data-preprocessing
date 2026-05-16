# 📚 Machine Learning Data Preprocessing - Learning Journey

A comprehensive collection documenting my hands-on learning journey in machine learning, featuring practical notebooks on data acquisition, exploratory data analysis, and real-world data preprocessing workflows.

## 🎯 Overview

This repository captures practical ML learning experiences with focus on real-world data handling - from fetching data from various sources to exploring patterns and preparing data for machine learning models. Each notebook documents a learning milestone with explanations, code, and insights.

**Perfect for:** ML beginners documenting their journey, practical learners, professionals needing reference implementations, and anyone learning data preprocessing workflows.

---

## 📁 Repository Structure

### 📥 Data Acquisition & Sources

#### API Data Fetching
- **[fetching_data_from_api.ipynb](fetching_data_from_api.ipynb)** - Retrieve data from REST APIs
  - HTTP requests and API calls
  - Handling JSON responses
  - Authentication and headers
  - Rate limiting considerations
  - Error handling and retries

#### Web Scraping
- **[webscrapping.ipynb](webscrapping.ipynb)** - Extract data from websites
  - BeautifulSoup fundamentals
  - HTML parsing and navigation
  - CSS selectors
  - Common scraping patterns
  - Ethical scraping practices

- **[webscrapping02.ipynb](webscrapping02.ipynb)** - Advanced scraping techniques
  - Multi-page scraping
  - Dynamic content handling
  - Data extraction strategies
  - Cleaning scraped data

#### Database & File Formats
- **[working_with_csv.ipynb](working_with_csv.ipynb)** - Load and manipulate CSV files
  - Reading CSV with pandas
  - Handling different delimiters
  - Data type inference
  - Missing value handling
  - Exporting to CSV

- **[ml04(working_with_json_and_sql).ipynb](ml04(working_with_json_and_sql).ipynb)** - JSON & SQL data
  - Parse JSON structures
  - Flatten nested JSON
  - Basic SQL queries
  - Connect to databases
  - Convert between formats

---

### 🔍 Data Exploration & Analysis

#### Exploratory Data Analysis (EDA)
- **[EDA(Exploratory_Data_Analysis).ipynb](EDA(Exploratory_Data_Analysis).ipynb)** - Comprehensive data exploration
  - Data shape and structure
  - Descriptive statistics
  - Missing value analysis
  - Outlier identification
  - Distribution analysis
  - Correlation analysis
  - Data quality assessment
  - Feature relationships

#### Visualization & Insights
- **[working_with_seaborn.ipynb](working_with_seaborn.ipynb)** - Advanced data visualization
  - Seaborn library basics
  - Distribution plots
  - Relationship plots
  - Categorical plots
  - Heatmaps and matrices
  - Multi-variable analysis
  - Customizing aesthetics
  - Saving high-quality figures

---

## 🚀 Quick Start

### Prerequisites
```bash
# Python 3.7+
# Required libraries:
pip install numpy pandas matplotlib seaborn requests beautifulsoup4 jupyter
```

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/imharshmishra87/Machine-Learning-data-preprocessing.git
   cd Machine-Learning-data-preprocessing
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt  # if available
   # OR manually install:
   pip install pandas numpy matplotlib seaborn requests beautifulsoup4
   ```

3. **Start Jupyter**
   ```bash
   jupyter notebook
   ```

4. **Open any notebook** and explore!

---

## 📚 Learning Paths

### Path 1: Data Acquisition (For Getting Started)
**Time: 2-3 hours**

1. `working_with_csv.ipynb` - Understand basic data loading
2. `fetching_data_from_api.ipynb` - Learn API data retrieval
3. `working_with_json_and_sql.ipynb` - Handle different formats

### Path 2: Web Data Extraction
**Time: 3-4 hours**

1. `webscrapping.ipynb` - BeautifulSoup fundamentals
2. `webscrapping02.ipynb` - Advanced scraping techniques
3. `working_with_csv.ipynb` - Save scraped data

### Path 3: Data Exploration & Analysis
**Time: 4-5 hours**

1. `EDA(Exploratory_Data_Analysis).ipynb` - Structured exploration
2. `working_with_seaborn.ipynb` - Create insightful visualizations

### Path 4: Complete Workflow (Comprehensive)
**Time: Full journey**

```
fetching_data_from_api.ipynb (Get Data)
    ↓
working_with_csv.ipynb (Load & Prepare)
    ↓
EDA(Exploratory_Data_Analysis).ipynb (Understand Data)
    ↓
working_with_seaborn.ipynb (Visualize Insights)
    ↓
Ready for ML Models! 🚀
```

---

## 🔧 Key Techniques Covered

| Technique | Notebook | Usage |
|-----------|----------|-------|
| **CSV Loading** | working_with_csv | Read/write local data files |
| **API Requests** | fetching_data_from_api | Fetch data from web services |
| **Web Scraping** | webscrapping, webscrapping02 | Extract data from websites |
| **JSON Parsing** | working_with_json_and_sql | Handle JSON structures |
| **SQL Queries** | working_with_json_and_sql | Query databases |
| **EDA** | EDA notebook | Understand data characteristics |
| **Visualization** | working_with_seaborn | Create insightful plots |

---

## 💡 What You'll Learn

### Data Acquisition Skills
✓ Load data from multiple sources (CSV, API, web, database)  
✓ Handle different data formats (JSON, CSV, SQL)  
✓ Fetch data using HTTP requests  
✓ Web scraping with BeautifulSoup  
✓ Error handling and data validation  

### EDA & Analysis Skills
✓ Structure exploratory analysis workflows  
✓ Compute statistical summaries  
✓ Identify missing values and outliers  
✓ Analyze feature distributions  
✓ Find correlations and patterns  

### Visualization Skills
✓ Create publication-quality plots  
✓ Choose appropriate chart types  
✓ Communicate data insights visually  
✓ Customize plot aesthetics  
✓ Multi-variable visualization techniques  

### Practical Skills
✓ Work with pandas DataFrames  
✓ Write clean, documented code  
✓ Handle real-world messy data  
✓ Debug data issues  
✓ Document your ML journey  

---

## 📊 Data Processing Workflow

```
Raw Data Sources
├── CSV/Excel Files ────────→ [working_with_csv]
├── Web APIs ────────────────→ [fetching_data_from_api]
├── Websites ────────────────→ [webscrapping]
├── JSON/SQL Databases ─────→ [working_with_json_and_sql]
└── Multiple formats

    ↓ [Combine & Standardize]

Unified DataFrame

    ↓ [Explore & Analyze]

[EDA notebook] - Structure your analysis

    ↓ [Visualize Results]

[Seaborn notebook] - Create insights

    ↓

Ready for Feature Engineering & Modeling! 🎯
```

---

## 🎓 Key Concepts

### CSV Data Handling
- Understand different delimiters and encodings
- Handle large files efficiently
- Deal with missing values during loading
- Type inference and conversion

### API Integration
- RESTful API fundamentals
- Request methods (GET, POST)
- Authentication tokens
- Pagination and rate limiting
- Error responses and status codes

### Web Scraping Ethics
- robots.txt and Terms of Service
- Respectful scraping practices
- Rate limiting your requests
- Legal considerations
- Alternatives to scraping

### JSON & SQL
- Nested JSON structure navigation
- Flattening hierarchical data
- Basic SQL SELECT queries
- Connecting to databases
- Joining and filtering data

### EDA Best Practices
- Start with shape and dtypes
- Systematically explore each feature
- Document your findings
- Create reproducible analyses
- Prepare insights for stakeholders

### Visualization Principles
- Choose the right chart for your data
- Color usage and accessibility
- Clear labels and titles
- Avoid misleading visualizations
- Tell a story with your plots

---

## 🌟 Real-World Applications

### Data Scientists
✓ Use as reference for data acquisition pipelines  
✓ Learn practical scraping and API techniques  
✓ Benchmark EDA approaches  

### Business Analysts
✓ Extract data from internal/external sources  
✓ Perform quick analyses  
✓ Create executive dashboards  

### ML Engineers
✓ Build data collection pipelines  
✓ Understand data quality issues  
✓ Document preprocessing steps  

### Learners
✓ Follow documented learning journey  
✓ Understand practical ML workflows  
✓ Build portfolio projects  

---

## 📋 Before You Start

### Checklist

- [ ] Python 3.7+ installed
- [ ] Jupyter notebook installed
- [ ] Required libraries installed
- [ ] Understand pandas basics
- [ ] Comfortable with Python functions
- [ ] Basic understanding of data structures

---

## 🛠️ Tools & Libraries Used

**Data Handling:**
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical operations

**Data Acquisition:**
- `requests` - HTTP requests for APIs
- `beautifulsoup4` - Web scraping
- `sqlite3` - Database queries

**Visualization:**
- `matplotlib` - Basic plotting
- `seaborn` - Statistical visualizations

**Development:**
- `jupyter` - Interactive notebooks
- `python` - Programming language

---

## 💡 Learning Tips

1. **Run Notebooks Sequentially** - Start with simple data loading, progress to complex analysis

2. **Modify Code** - Change parameters, try different approaches, experiment!

3. **Work with Your Own Data** - Take the techniques and apply to datasets you care about

4. **Document Your Learning** - Add comments explaining what you learned from each step

5. **Follow Best Practices** - Use error handling, validate data, document assumptions

6. **Build Projects** - Combine multiple notebooks to create end-to-end pipelines

---

## 🚀 Next Steps

After mastering these notebooks:

1. **Feature Engineering** - Learn scaling, encoding, feature creation
2. **Model Building** - Apply ML algorithms (regression, classification)
3. **Evaluation** - Measure model performance
4. **Deployment** - Put models in production
5. **Documentation** - Write clear project documentation

---

## 📚 Resources & References

**Documentation:**
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Guide](https://matplotlib.org/stable/contents.html)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [BeautifulSoup Docs](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Requests Library](https://requests.readthedocs.io/)

**Learning Resources:**
- Real Python tutorials
- Kaggle datasets and kernels
- Official library documentation
- Stack Overflow for troubleshooting

---

## 📝 Common Challenges & Solutions

### Challenge: API Rate Limiting
**Solution:** Implement delays between requests, use API tokens, respect rate limits

### Challenge: Web Scraping Blocked
**Solution:** Rotate user agents, add delays, respect robots.txt, consider alternatives

### Challenge: Large CSV Files
**Solution:** Use chunks, filter during loading, use appropriate data types

### Challenge: Messy Real-World Data
**Solution:** EDA first to identify issues, handle systematically, document assumptions

### Challenge: Understanding EDA Results
**Solution:** Visualize everything, compare distributions, check relationships

---

## 🤝 Contributing

Have improvements or found issues?
- Suggest new techniques
- Report bugs in notebooks
- Share your learning experiences
- Contribute your own notebooks

---

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

---

## 🔗 Related Repositories

🤖 **[ML-models](https://github.com/imharshmishra87/Ml-models)** - Machine learning algorithm implementations

📊 **[Feature-Scaling-ML](https://github.com/imharshmishra87/Feature-Scaling-ML)** - Feature engineering and preprocessing techniques

---

## 💬 Let's Connect

This is a learning journey - share your progress, ask questions, and grow together!

---

**Last Updated:** May 2026  
**Status:** Active Learning  
**Contributions:** Encouraged and Welcomed  

⭐ **If this helps your ML journey, please star this repository!**

---

## 📌 Quick Navigation

- [CSV Loading](#) - `working_with_csv.ipynb`
- [API Fetching](#) - `fetching_data_from_api.ipynb`
- [Web Scraping](#) - `webscrapping.ipynb`, `webscrapping02.ipynb`
- [Data Exploration](#) - `EDA(Exploratory_Data_Analysis).ipynb`
- [Visualization](#) - `working_with_seaborn.ipynb`
- [JSON & SQL](#) - `ml04(working_with_json_and_sql).ipynb`

---

**Happy Learning! 🚀 Keep exploring, keep learning, keep improving!**
