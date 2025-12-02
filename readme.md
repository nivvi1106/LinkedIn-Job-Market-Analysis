# LinkedIn Job Posting Analysis

This project analyzes **7,900+ LinkedIn job postings** to uncover hiring trends, high-demand roles, competitive companies, and future skill demand.  
Using Python (Pandas, Seaborn, Matplotlib, Scikit-Learn), the project includes exploratory data analysis, skill extraction, and a simple linear regression model to forecast rising skills.

---

## Dataset  
The dataset used in this project was sourced from Kaggle:

🔗 **LinkedIn Job Data (Kaggle)**  
https://www.kaggle.com/datasets/shashankshukla123123/linkedin-job-data

*(Dataset not included in this repository due to size — download from link above and upload into the notebook when running.)*

---

## Project Highlights

### **1. Exploratory Data Analysis (EDA)**
- Analyzed **7,900+ job postings** to identify:
  - Top hiring cities  
  - Most in-demand job roles  
  - Most active hiring companies  
  - Competitive positions (roles receiving high applications)  
  - Work type distribution (Remote / On-site / Hybrid)
- Extracted and ranked common skills from job descriptions.

### **2. Skill Demand Forecasting (Machine Learning)**
A simple **Linear Regression model** was used to forecast future skill demand by analyzing skill mentions across three time groups:
- Older postings  
- Mid-range postings  
- Recent postings  

**Key insights:**
- **AI demand projected to rise ~15%** in future periods.  
- **UI/UX shows strong upward trend (~12%).**  
- Traditional skills like **Python, SQL, and Java** show declining trajectories in recent postings.  

This simple model provides a forward-looking view into evolving job-market skill requirements.

---

## Tech Stack

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-Learn (Linear Regression)**
- **Regular Expressions (for skill extraction)**

---

## How to Run This Project

### **Option A — Run on Google Colab**
1. Open `LinkedIn_Job_Market_Analysis.ipynb` in Colab.  
2. Download the dataset from Kaggle.  
3. Upload `linkdin_Job_data.csv` to Colab.  
4. Run all cells.

### **Option B — Run Locally**
```bash
git clone https://github.com/nivvi1106/LinkedIn-Job-Posting-Analysis.git
cd LinkedIn-Job-Posting-Analysis
Then open the notebook in Jupyter or VS Code
```

## Visuals Included

The notebook includes clear visualizations, such as:
1. Top 10 hiring locations
2. Top hiring companies
3. Most competitive job roles
4. Work type distribution
5. In-demand skill rankings
6. Forecasted skill-growth curves (AI, UI/UX, etc.)

## Key Results Summary

1. AI is the fastest-growing skill (projected +15%).
2. UI/UX demand is steadily increasing (+12%).
3. Job postings for Data Analyst, Developer, and Manager roles appear most frequently.
4. Cities like Bengaluru, Hyderabad, and Chennai show the highest job activity.
5. Companies with high LinkedIn follower counts receive more applications on average.


## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
