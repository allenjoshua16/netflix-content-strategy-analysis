# Netflix Content Strategy Analysis
## Project Overview
This project analyzes Netflix genre trends through a business strategy lens, not just exploratory data analysis.

Instead of only visualizing genre distributions, the objective was to simulate how a Data Analyst might support content investment decisions by answering questions such as:

* Which genres accelerated during COVID?
* Which genres show consistent long-term growth?
* Which high-volume categories are too volatile to rely on?
* Where should strategic content investment be prioritized?

The result is a structured, decision-oriented analytics pipeline.

## Dataset
* Source: Netflix titles dataset
* Records: 8,800+ titles
* Time Range: 2008 – 2021
* Categories: Movies and TV Shows

## Analytical Framework
The project was built as a modular pipeline using Python and Pandas.

1️⃣ Year-over-Year Genre Growth
Calculated annual title counts per genre and computed percentage growth to identify acceleration patterns.

2️⃣ Volatility Measurement
Measured standard deviation across time to quantify genre instability.

3️⃣ Risk-Adjusted Opportunity Score
Developed a scoring model that balances:
* Average long-term growth
* Volatility
* Consistency

This prevents overvaluing high-growth but unstable segments.

4️⃣ COVID Momentum Analysis
Compared pre-2020 and post-2020 growth to detect pandemic-driven shifts in content demand.

5️⃣ Strategic Quadrant Modeling
Built a quadrant framework using:
* X-axis: Average Titles per Year
* Y-axis: Volatility

This allows genres to be classified into strategic categories such as:
* Growth Engines
* Stable Core
* Emerging Opportunities
* Niche Segments

## Key Findings
* International Movies and Dramas dominate long-term sustained volume.
* Certain niche genres experienced disproportionate COVID acceleration.
* Mid-volume genres with controlled volatility surfaced as strong strategic opportunities through risk-adjusted scoring.
* Some high-volume categories show instability, suggesting allocation risk.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* seaborn
* Time-Series Growth Modeling
* Feature Engineering
* Strategic Quadrant Analysis

## Visual Outputs
* Top COVID Growth Genres
* Genre Volatility Analysis
* Strategic Quadrant Classification
* Risk-Adjusted Opportunity Table

## Business Value
This project demonstrates:
* Analytical thinking beyond visualization
* Metric engineering aligned with business decisions
* Risk-aware modeling
* Structured pipeline development
* Strategic storytelling through data

## Future Improvements

* Add engagement metrics (if available)
* Incorporate external demand signals
* Extend quadrant model with clustering
* Deploy interactive dashboard version

## 👨‍💻 Author

Allen Joshua 
Master’s in Data Science | Aspiring Data Analyst  
Open to Data Analytics opportunities
