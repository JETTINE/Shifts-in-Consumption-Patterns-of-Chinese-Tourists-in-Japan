Japan Inbound Tourism Data Analysis
A Python data-analysis project based on tourism statistics collected for my master's research at Shizuoka University.
This project analyzes changes in the geographic concentration and total consumption of Chinese visitors to Japan using public tourism statistics from JNTO and the Japan Tourism Agency.
Tech Stack
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Excel
What I Implemented
- Read and organized Excel-based tourism statistics with Pandas
- Cleaned numeric fields and handled missing values
- Analyzed annual and quarterly HHI trends
- Visualized time-series changes with Matplotlib
- Compared pre-pandemic and post-pandemic tourism spending
- Structured the analysis in a reproducible Jupyter Notebook
Analysis
1. Annual HHI Trend
The Herfindahl-Hirschman Index (HHI) is used to measure the geographic concentration of visitor destinations.
A higher HHI indicates stronger concentration, while a lower HHI indicates greater geographic dispersion.
The annual data show that the HHI declined from 0.1423 in 2023 to 0.1246 in 2025, suggesting that the post-pandemic concentration of Chinese visitors has gradually eased.
2. Quarterly HHI Trend
Quarterly data from 2023 to 2025 are analyzed to examine short-term and seasonal changes in destination concentration.
The notebook visualizes how the HHI changed across quarters and makes it easier to compare post-pandemic recovery patterns.
3. Total Tourism Consumption
Annual total spending by Chinese visitors is analyzed using tourism statistics in the source workbook.
The comparison shows:
- 2019: 17,704 hundred million JPY
- 2024: 17,335 hundred million JPY
- Change from 2019 to 2024: approximately -2.08%
Missing values for the pandemic years are kept as missing observations rather than artificially filled.
Project Files
.
├── README.md
├── tourism_analysis.ipynb
└── データ統計.xlsx
- tourism_analysis.ipynb — executable analysis notebook with code, tables, and charts
- データ統計.xlsx — source workbook used in the analysis
How to Run
1. Download this repository.
2. Make sure tourism_analysis.ipynb and データ統計.xlsx are in the same folder.
3. Install the required Python packages:
pip install pandas matplotlib openpyxl jupyter
4. Open the notebook:
jupyter notebook tourism_analysis.ipynb
5. Run the cells from top to bottom.
Data Sources
The workbook was compiled from publicly available tourism statistics, including data from:
- Japan National Tourism Organization (JNTO)
- Japan Tourism Agency
Skills Demonstrated
This project demonstrates practical experience in:
- Python-based data processing
- Pandas data cleaning and transformation
- Excel data ingestion
- Missing-value handling
- Time-series analysis
- HHI-based concentration analysis
- Data visualization with Matplotlib
- Reproducible analysis using Jupyter Notebook
- GitHub-based project documentation
日本語概要
本プロジェクトは、修士研究で収集した訪日観光統計を用い、中国人訪日客の訪問地域の集中度および消費動向を分析したものです。
Python・Pandasを用いてExcelデータの読み込み、整理、欠損値処理を行い、HHI（ハーフィンダール・ハーシュマン指数）の年次・四半期推移を分析しました。また、Matplotlibを用いて時系列データを可視化し、2019年と2024年の訪日消費総額の比較も行っています。
このリポジトリでは、分析コード、出力結果、使用データをJupyter Notebook上で確認できます。
Note
This repository is a simplified and reproducible version of part of my master's research on changes in the consumption behavior of Chinese visitors to J
