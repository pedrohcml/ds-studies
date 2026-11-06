# ds-studies

Notebooks I wrote during my data science studies, involving machine learning, statistics, data treatment, applied AI etc.

## Content

| Folder | Theme | Topics |
|-------|------|---------|
| `AI Agents, LLMs and NLP/` | LLMs and NLP | GPT, RAG, Text mining, Transformers |
| `Charts, Visualization and Dashboards/` | Charts and dashboards | Pie charts, Boxplots, Histograms, Density charts, Bar charts, Scatter plots, Seaborn, Matplotlib |
| `Data treatment/` | Data treatment | Data treatment |
| `Deep Learning/` | Neural networks | Deep Learning, Neural net |
| `Final test/` | Testing my knowledge | Defaulting predicition |
| `Graphs/` | Graph Theory | Graphs, Metrics, Paths and distances, Printing paths |
| `Intro Python/` | Back to the basics | Conditions, Dictionaries, sets and tuples, Functions, Lists, Loops, NumPy, pandas |
| `Lab/` | Final lab | Wine classification with GaussianNB |
| `Linear Regression/` | Linear regression | Simple and multiple linear regression |
| `Logistic Regression/` | Logistic regression | Logistic regression and activation functions |
| `Machine Learning/` | ML algorithms | Attribute selection, Apriori and ECLAT, Decision tree, Random Forest (EL), K-means, C-means, K-medoids, Instance based learning, Naive Bayes |
| `MongoDB/` | Connecting with MongoDB | Connection |
| `SQL/` | Connecting with PostgreSQL | Connection |
| `Statistics 1/` | Statistics | Centrality and variability measures, Normal distribution, Normality tests, Sampling |
| `Statistics 2/` | Statistics | ANOVA, Binomial, Chi-square, Poisson, T-student |
| `Time Series/` | Time series | ARIMA, Decomposition |

## Used libraries

Python · Jupyter · pandas · NumPy · scikit-learn 
scipy · Matplotlib · mpl_toolkits · Seaborn · Wordcloud 
Graphviz · XGBoost · Yellowbrick · SHAP · PyClustering 
SKFuzzy · Apyori · Keras · PyTorch · Transformers 
Statsmodels · PMDARIMA · igraph · NLTK · Groq
Langchain · psycopg2 · pymongo · statistics · datetime
os · argparse · math · optparse · string · sys

## How to execute

```bash
git clone https://github.com/pedrohcml/ds-studies.git
cd ds-studies
python -m venv venv
venv\Scripts\activate        # Windows
pip install -r requirements.txt
jupyter lab
```

## API keys

The LLM notebooks use Groq's API. Define the key as an environment variable
before opening Jupyter:

```bash
set GROQ_API_KEY=sua_chave      # Windows (CMD)
```

## Datasets

The datasets are not versioned. The sources are indexed at the beginning of each notebook.
