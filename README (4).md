# Netflix Data Analysis

This project explores the **Netflix dataset** (`netflix_titles.csv`) to uncover insights about movies and TV shows available on the platform.  
It uses **Python, Pandas, and Matplotlib** for data cleaning, analysis, and visualization.

---

## Dataset
The dataset contains information about movies and TV shows on Netflix, including:
- **type** → Movie or TV Show  
- **title** → Name of the content  
- **director / cast** → People involved  
- **country** → Country of production  
- **date_added** → Date when added to Netflix  
- **release_year** → Year of original release  
- **rating** → TV rating (PG, R, etc.)  
- **duration** → Minutes (for movies) / Seasons (for TV shows)  
- **listed_in** → Genres/categories  
- **description** → Short summary  

---

## Key Analyses

### 1. Movies vs TV Shows
- Count and visualize how many **movies vs TV shows** are available on Netflix.

### 2. Most Prolific Directors
- Identify directors with the highest number of titles on Netflix.

### 3. Average Show Times
- Calculate:
  - Average **movie duration** (minutes).  
  - Average **TV show length** (seasons).  

### 4. Longest Movies
- Find the **top 10 longest movies** available on Netflix.

### 5. Content Released Per Year
- Explore how many titles were originally **released each year**.  
- Compare growth in movies vs TV shows.

### 6. Content Added to Netflix
- Use the **`date_added`** column to find:
  - Which year Netflix added the most titles.  
  - Trends in yearly additions.  

### 7. Genre Trends Over Time
- Analyze genres from the **`listed_in`** column.  
- Track the growth of top genres (e.g., Dramas, Documentaries, Comedies) over the years.

---

## Visualizations
Some key plots include:
- Pie chart: Movies vs TV Shows  
- Bar chart: Most prolific directors  
- Histogram: Duration distribution  
- Line chart: Content released/added per year  
- Line/area chart: Genre trends  

---

## Tech Stack
- **Python**  
- **Pandas** → Data cleaning & analysis  
- **Matplotlib** → Visualization  
- (Optional) **Jupyter Notebook** for interactive exploration  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/hrishavraj89/netflix_data_analysis.git
   ```
2. Install dependencies (create a virtual environment if needed):
   ```bash
   pip install pandas matplotlib jupyter
   ```
3. Open the notebook:
   ```bash
   jupyter notebook netflix_data_analysis.ipynb
   ```
4. Run the cells to reproduce the analysis.

---

## Future Improvements
- Add interactive dashboards (e.g., Plotly, Dash).  
- Perform deeper **NLP analysis** on the description column.  
- Explore **country-wise content distribution**.  

---

## License
This project is for educational and learning purposes.
