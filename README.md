# Addition-Financial-Competition-2023-2024

Team Members:
- Nisshanth Perumalsamy
- Daniel Wilson
- Nathan Collazo
- Jovany Perez

This README documents the comprehensive analysis conducted by Jovany Perez, Nisshanth Perumalsamy, Daniel Wilson, and Nathan Collazo from the University of Central Florida under the course STA 4724, Big Data Analytics, instructed by Dr. HanQin Cai, focusing on Addition Financial Credit Union's data to recommend optimal locations for new branches.

# Abstract
This study analyzes Addition Financial Credit Union's branch and member level data from January 2022 to July 2023, focusing on identifying the best location for a new branch. Using advanced analytical techniques such as PCA, Random Forest Regression/Classification, K-Means clustering, IDW, and KNN, we examined transaction counts, member activities, and branch performances. Our findings suggest Orange County, with Ocoee as the ideal city for a new branch, leveraging internal and external data sources to inform our recommendation.

# Objectives
Our primary objective is to determine the most suitable location for a new branch of Addition Financial Credit Union. We aimed to understand transaction patterns, demographic influences, and the potential of advanced data analysis techniques in optimizing branch location. Our questions focused on the interplay between transaction patterns, member engagement, demographic factors, and branch performance to guide strategic expansion.

# Data Sources
Data were sourced from internal records of Addition Financial Credit Union and external public sources, including county-level employment rates and demographic statistics, yielding over 1.6 million member records and 700+ branch records. External data included population statistics, employment data, and economic indicators from various credible sources, providing a rich dataset for analysis.

# Study Environment
The analysis utilized Windows 11 and macOS machines equipped with at least 16GB RAM, running Python3 via Anaconda in Jupyter Labs and VScode, ensuring reproducibility across different computing environments.

# Methodology Overview
Our analysis proceeded in four phases, each building upon the insights and methodologies of the previous to refine our understanding and recommendations:

  Phase 1: Data exploration and preprocessing, including PCA for pattern identification.
  Phase 2: Analysis of external data with Random Forest and KNN to predict optimal counties for new branches.
  Phase 3: Time-series analysis and Random Forest classification of internal data to distinguish high-performing                 branches and areas.
  Phase 4: Focused analysis on Orange County using advanced spatial modeling techniques to identify Ocoee as the                 prime location for expansion.
  
# Key Findings
- Orange County and St.Johns County emerged as a prime candidate for new branch locations, with a detailed assessment supporting Ocoee as the ideal city.
- Advanced analytical techniques, when applied to both internal and external data, provided deep insights into optimal branch locations, balancing transaction volumes, demographic trends, and economic indicators.
- The integration of multiple data sources and analytical methods was essential in forming a comprehensive view of strategic opportunities for branch expansion.

# Conclusion
The multi-phased analysis of Addition Financial Credit Union's data illuminated the strategic importance of Orange County, with a particular emphasis on Ocoee for branch expansion. This detailed study showcases the potential of combining internal transaction data with external demographic and economic data to inform strategic business decisions.

# Appendix
References include works by Kleinbaum et al., McKinney, and various data sources such as World Population Review, Wikipedia, and official state and county resources, underlining the extensive and diverse data utilized in this analysis.

# External Libraries Used
statsmodels: For statistical modeling and hypothesis testing.
plotly.express: For interactive and visually appealing charts and graphs.
mpl_toolkits.mplot3d: For basic 3D plotting capabilities.
Requests: For sending HTTP requests and interacting with web services.
Geopandas: For handling geospatial data.








