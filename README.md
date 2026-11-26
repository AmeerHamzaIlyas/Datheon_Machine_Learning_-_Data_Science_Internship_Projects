# Datheon_Machine_Learning_-_Data_Science_Internship_Projects

## Task 1 Documentation:
  Task 1 describes multi-class classificaion problem pipeline in machine learning. This uses a famous dataset named Iris to solve this type of problem in using scikit learn (preprocessing, model selection, evaluation-metrics etc) and other python libararies like pandas for data handling, numpy for numeric calculations, Matplolib for visualization and seaborn for pairplots and heatmaps.

1.  Supporting libraries:
(a) Pandas
(b) Numpy
(c) Matplotlib
(d) Seaborn
(e) Scikit-learn

2.  Load Dataset:
df = pd.read_csv("dataset-url")
df.head()

3.  Basic Dataset Inspection:
df.describe()
df.info()
df.isnull().sum()
df.nuniques()

4.  EDA Pair Plots:
sns.pairplot(df,hue="species")
