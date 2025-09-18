# The American Labor Story: A Tale of Two Futures (1983-2022)

This repository contains an exploratory data analysis (EDA) of U.S. Bureau of Labor Statistics (BLS) data from 1970-2020. It argues that there isn't one "American Labor Story," but two diverging ones, fundamentally challenging the common narrative of uniform union decline.

## 💡 Key Findings & Central Themes

1.  **The Great Divergence (Public vs. Private):** The precipitous decline in U.S. union density is almost exclusively a **private-sector phenomenon.** In stark contrast, public sector union density has not only remained robust but has often *grown*, indicating two distinct and economically divergent labor movements. This divergence is the central explanatory variable for understanding the current state of American labor.
![Two stacked bar graphs. On the left, we have the total number of private and public sector union workers; on the right, the percentage of the private and public sector workforce that belongs to a union.  In 1983, there were about 12 million private sector union members, or around 17% of the workforce.  By 2022, this had declined to under 8 million members, around 9% of the private sector workforce.  Over the same timeframe, public sector union membership expanded from around 6 to around 7 million, holding steady at around 35% of the public sector workforce.](assets/public_private_union_members.png) 
    
2.  **The Causal Conundrum: Strikes and Membership:** The data reveals a counter-intuitive temporal relationship: the dramatic decrease in major labor actions (work stoppages involving 1,000 or more workers) **precedes** the sharpest declines in private-sector union membership. This suggests that a decline in the *capacity* and *willingness* to strike, and therefore a perceived reduction in union efficacy, may have directly contributed to the erosion of private-sector union power. This challenges the common assumption that declining membership *causes* fewer strikes; instead, fewer strikes (and thus less perceived power) preceded declining membership.
![A line graph showing active work stoppages and percentage of days idle in the US from 1947-2022.  The graph plainly shows a dramatically higher rate of work stoppages from the late 1940's through the 1970's.  Starting in the early 1980's both graphs remain low and less volatile, with under 50 work stoppages/year and well under 0.05% of workdays idle.](assets/work_stoppages.png) 

## 📊 Data Sources & Methodology

This analysis utilizes publicly available historical data from the U.S. Bureau of Labor Statistics (BLS), specifically focusing on:
* Union Membership, Density, and Coverage by Sector (Private Wage & Salary Workers, Government Workers)
* Major Work Stoppages (1,000 or More Workers)

The methodology employs standard data wrangling, time-series analysis, and compelling visualization techniques using Python's data science ecosystem to extract and present these critical insights.

## 🛠 Tech Stack

* **Python 3.x**
* **Pandas:** For robust data manipulation and analysis.
* **NumPy:** For efficient numerical operations.
* **Matplotlib / Seaborn:** For creating high-quality, illustrative statistical visualizations.
* **Jupyter Lab:** For interactive data exploration and reproducible analysis.

## 🚀 How to Replicate

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourGitHubUsername/american-labor-actions.git](https://github.com/YourGitHubUsername/american-labor-actions.git)
    cd american-labor-actions
    ```
2.  **Set up Environment:**
    ```bash
    # It's recommended to use a virtual environment for dependency management
    python -m venv venv
    source venv/bin/activate # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
3.  **Run the Analysis:**
    ```bash
    jupyter lab
    ```
    Open the `american_labor_actions.ipynb` notebook and execute all cells. The complete analysis, data processing steps, and all visualizations will be generated dynamically.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Contributions & Feedback

Insights and alternative interpretations are highly encouraged. Please feel free to open an issue or submit a pull request if you have suggestions for expanding the analysis or improving the presentation.
