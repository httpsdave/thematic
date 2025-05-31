# thematic

Research Trends Analysis
Automated analysis of research themes and trends in thesis/capstone abstracts using NLP and statistical methods.


Install requirements:
!pip install numpy==1.23.5 scipy==1.10.1 gensim==4.3.0 --force-reinstall

Add your data:
Place your CSV file named trend_analysis dataset.csv in the project folder
Required columns: Title, Abstract Keywords, Year, Program

What it does

Identifies 5 major research themes using topic modeling
Shows trends over time (2005-2023)
Compares thesis vs capstone projects
Generates visualizations and statistical insights
Analyzes research methodology patterns

Output
The script automatically generates:

Word clouds and frequency charts
Theme distribution plots
Trend analysis graphs
Statistical significance tests
Industry alignment analysis

Just drag the CSV file and run the script.
