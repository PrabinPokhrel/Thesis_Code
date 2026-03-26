# 📘 Thesis Project: Topic Modeling on SDG-related Research in Nepal (2015–2024)

This repository contains all source code, data samples, and outputs used in my master's thesis titled:

**"Analyzing Research Trends in Sustainable Development Goals (SDGs) in Nepal Using Topic Modeling (2015–2024)"**

The thesis applies BERTopic for topic modeling on metadata from SDG-related research to explore emerging themes, temporal trends, and SDG distribution.


## 📁 Repository Structure

├── data/

│ ├── sdg1_no_poverty.csv

│ ├── sdg2_zero_hunger.csv

│ └── ... (all 17 SDG datasets)

├── output_topics/

│ ├── bertopic_summary.csv

├── notebooks/

│ └── thesis_code.ipynb

├── README.md

## 📝 Appendices (as per thesis)

- **Appendix A**: Source datasets for each of the 17 SDGs (`/data/`)
  
- **Appendix B**: BERTopic topic summary output (`/output_topics/bertopic_keywords.csv`)
  
- **Appendix C**: Complete source code for preprocessing, topic modeling, and RQ answers (`/notebooks/thesis_code.ipynb`)


## 🧠 Technologies Used

- Python 3.x
  
- [BERTopic]
  
- Pandas, NumPy, Matplotlib, Scikit-learn
  
- Jupyter Notebook
