# 🦠 COVID-19 Global Data Tracker

A data analysis project that tracks global COVID-19 trends—cases, deaths, recoveries, and vaccinations—across countries and through time. You shall uncover insights, visualize data, and present findings worthy of the court of knowledge.

---

## 🎯 Project Objectives

- 🧹 Import and clean global COVID-19 data from Our World in Data
- 📈 Analyze time-based trends: total cases, new cases, deaths, and vaccinations
- 🌍 Compare metrics across nations (e.g., Kenya, USA, India)
- 📊 Visualize data with line charts, bar graphs, and optional choropleth maps
- 📝 Communicate findings through narrative insights and visual reports

---

## 🛠 Tools and Libraries Used

- Python (3.8+)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [plotly](https://plotly.com/python/) _(optional for maps)_
- [Jupyter Notebook](https://jupyter.org/)

---

## 🧪 How to Run / View the Project

1. **Clone the repository**

   ```
   git clone `repo_url`
   cd Covid-19

   ```

2. **Install Dependencies**

   ```
   pip install -r requirements.txt

   ```

3. **Download the dataset**
   Download the owid-covid-data.csv from Our World in Data and place it in the data/ folder.

4. **Run the analysis notebook**
   Launch Jupyter Notebook:
   `jupyter notebook notebooks/analysis.ipynb`

5. **View visualizations**

- Charts will be saved in outputs/charts/
- Export notebook as PDF or slideshow for presentation

## Sample Insights

- 🇺🇸 The United States reported the highest total cases and vaccinations.
- 🇮🇳 India had sudden surges in cases around May 2021.
- 🇰🇪 Kenya maintained a lower death rate compared to global giants.
- Vaccination rates vary widely—early rollouts impacted overall case trends.
- Most countries saw a rise in new cases before vaccination peaks.
