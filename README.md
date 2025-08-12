Movie Rating Analysis
### 1. Business Understanding
The goal is to explore and understand movie rating data identifying the highest-rated movies, vote distribution, and relationships between ratings and popularity.

### 2. Data Understanding
The dataset contains information for 5 movies:

### Structure


Rows:

5 (each row represents a unique movie or TV title)

Columns:

tconst → Unique identifier for a title (e.g., IMDb ID)

averageRating → Average user rating (scale: 1–10)

numVotes → Number of votes received

### 3. Data Preparation
The data is structured in a pandas DataFrame. Initial steps include loading the data and inspecting for missing values.

### 4. Modeling
No complex models are built in this example, but basic visualizations are used to understand the data:

Violin plots, 
Correlation heatmaps,
Boxplot
### 5. Evaluation
Key findings:

Highest rated movie: tt10384606 (8.9 rating)

Most voted movie: tt1043726 (50,352 votes)

Weak correlation between rating and number of votes in this small dataset

### 6. Deployment
This notebook serves as a starting point for larger movie datasets or recommendation engines. The code and visualizations can be adapted and extended easily.

