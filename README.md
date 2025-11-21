# Boston Housing Analysis with PySpark

Exploratory Data Analysis of the Boston Housing dataset using Apache Spark in Google Colab.

## Overview

This project performs EDA on 506 Boston housing observations using PySpark, demonstrating distributed data processing, statistical analysis, and visualization techniques.

## Tasks Completed

1. ✅ Load CSV with schema inference
2. ✅ Display first 5 rows
3. ✅ Count observations (506 total)
4. ✅ Show dataset schema
5. ✅ Drop column 'b'
6. ✅ Round numeric columns to 2 decimals
7. ✅ Create Age10 column (age × 1.10)
8. ✅ Plot Age10 histogram
9. ✅ Generate summary statistics
10. ✅ Convert to Pandas and show last 5 rows

## Tech Stack

- **Spark**: 3.5.1
- **Python**: 3.8+
- **Platform**: Google Colab
- **Libraries**: PySpark, pandas, matplotlib

## Quick Start

```bash
# Clone repo
git clone https://github.com/YOUR_USERNAME/boston-housing-pyspark-analysis.git

# Upload to Google Colab
# - boston_housing_analysis.py
# - BostonHousing.csv

# Run the script
!python boston_housing_analysis.py
```

The script auto-installs Java 8, downloads Spark 3.5.1, and executes all analysis tasks.

## Results

- **506 observations**, 13 features (after dropping 'b')
- **No missing values**
- Age10 histogram reveals housing age distribution patterns
- Complete summary statistics computed

## Files

```
boston-housing-pyspark-analysis/
├── README.md
├── boston_housing_analysis.py
├── BostonHousing.csv
├── REPORT.md
└── requirements.txt
```

## Reflections

See [REPORT.md](REPORT.md) for detailed analysis of:
- How visualization enhances Spark data understanding
- Challenges encountered
- Interesting discoveries

## Author

Ritik shah  
Big Data Analytics Course

## License

MIT
