📊 Project 2 – Statistical Plots & Distribution Analysis
📌 Overview
This project performs statistical distribution analysis on the 10000 Sales Records dataset using Python. The objective is to explore the distribution of numerical variables, compare distributions across groups, detect outliers, and interpret skewness and spread using visualizations.

🎯 Objectives
Draw Histograms and Kernel Density Estimation (KDE) plots

Create Boxplots to inspect spread and outliers

Compare distributions across groups (e.g., Region-wise analysis)

Detect outliers using the IQR method

Analyze skewness and standard deviation

Export plots and generate a one-paragraph interpretation

🗂 Dataset Used
File: 10000 Sales Records.csv
Key Columns Used:

Region

Total Profit (Primary numerical variable for analysis)

🛠 Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy

📈 Analysis Performed
1️⃣ Histogram + KDE
Visualizes the overall distribution of Total Profit to understand its density and shape.

2️⃣ Boxplot (Overall)
Shows:

Median

Interquartile Range (IQR)

Outliers

3️⃣ Group Comparison (Region-wise)
Boxplot comparison of Total Profit across regions

Region-wise histogram with KDE

4️⃣ Outlier Detection
Outliers were identified using the Interquartile Range (IQR) Method:

L
o
w
e
r
B
o
u
n
d
=
Q
1
−
1.5
×
I
Q
R
U
p
p
e
r
B
o
u
n
d
=
Q
3
+
1.5
×
I
Q
R
LowerBound=Q1−1.5×IQRUpperBound=Q3+1.5×IQR
5️⃣ Skewness & Spread
Mean

Median

Standard Deviation

Skewness

📊 Key Insights
The distribution shows variation in profitability across regions.

Presence of outliers indicates extreme profit values in certain transactions.

Skewness suggests whether profit distribution is symmetric or biased toward higher/lower values.

Some regions demonstrate higher variability in profit margins.

📁 Output Files Generated
histogram_kde.png

boxplot_overall.png

boxplot_by_region.png

histogram_by_region.png

interpretation.txt

▶ How to Run
Install required libraries:

pip install pandas numpy matplotlib seaborn scipy
Place the dataset file in the project directory.

Run the Python script:

python project2_analysis.py
📌 Conclusion
This project demonstrates practical application of statistical visualization techniques to understand data distributions, detect anomalies, and compare performance across categories. It highlights how exploratory data analysis (EDA) supports data-driven decision-making.

If you'd like, I can also make:

⭐ A more polished "portfolio-style" README

📊 A version with embedded images

🚀 A resume-ready project description

🎓 A university submission version

Just tell me what you need.




Voice
We use cookies

We use cookies to help this site function, understand service usage, and support marketing efforts. Visit Manage Cookies to change preferences anytime. View our Cookie Policy for more info.


Manage Cookies

Reject non-essential

Accept all

Python Code for Statistical Analysis
You’re viewing user-generated content that may be unverified or unsafe.
Report
Here’s a clean, professional README.md you can paste directly into GitHub for your project.

📊 Project 2 – Statistical Plots & Distribution Analysis
📌 Overview
This project performs statistical distribution analysis on the 10000 Sales Records dataset using Python. The objective is to explore the distribution of numerical variables, compare distributions across groups, detect outliers, and interpret skewness and spread using visualizations.

🎯 Objectives
Draw Histograms and Kernel Density Estimation (KDE) plots

Create Boxplots to inspect spread and outliers

Compare distributions across groups (e.g., Region-wise analysis)

Detect outliers using the IQR method

Analyze skewness and standard deviation

Export plots and generate a one-paragraph interpretation

🗂 Dataset Used
File: 10000 Sales Records.csv
Key Columns Used:

Region

Total Profit (Primary numerical variable for analysis)

🛠 Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy

📈 Analysis Performed
1️⃣ Histogram + KDE
Visualizes the overall distribution of Total Profit to understand its density and shape.

2️⃣ Boxplot (Overall)
Shows:

Median

Interquartile Range (IQR)

Outliers

3️⃣ Group Comparison (Region-wise)
Boxplot comparison of Total Profit across regions

Region-wise histogram with KDE

4️⃣ Outlier Detection
Outliers were identified using the Interquartile Range (IQR) Method:

L
o
w
e
r
B
o
u
n
d
=
Q
1
−
1.5
×
I
Q
R
U
p
p
e
r
B
o
u
n
d
=
Q
3
+
1.5
×
I
Q
R
LowerBound=Q1−1.5×IQRUpperBound=Q3+1.5×IQR
5️⃣ Skewness & Spread
Mean

Median

Standard Deviation

Skewness

📊 Key Insights
The distribution shows variation in profitability across regions.

Presence of outliers indicates extreme profit values in certain transactions.

Skewness suggests whether profit distribution is symmetric or biased toward higher/lower values.

Some regions demonstrate higher variability in profit margins.

📁 Output Files Generated
histogram_kde.png

boxplot_overall.png

boxplot_by_region.png

histogram_by_region.png

interpretation.txt

▶ How to Run
Install required libraries:

pip install pandas numpy matplotlib seaborn scipy
Place the dataset file in the project directory.

Run the Python script:

python project2_analysis.py
📌 Conclusion
This project demonstrates practical application of statistical visualization techniques to understand data distributions, detect anomalies, and compare performance across categories. It highlights how exploratory data analysis (EDA) supports data-driven decision-making.

