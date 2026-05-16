# India's EV Transition — State-wise Adoption Trends & Forecasting

Applied Statistics (AIDS) Project — AE 248 Course, IIT Bombay

## Team

| Roll No. | Name |
|---|---|
| 24B0006 | B. Ravindra |
| 24B0022 | M. Jaswanth Narayana |
| 24B0047 | S. Sai Balaji |
| 24B0030 | C. Mahith Kumar Reddy |

## About

This project analyses India's electric vehicle adoption trends from 2014 to 2024 using
monthly fuel-type wise and state-wise vehicle registration data from MoRTH (data.gov.in).
The analysis covers exploratory visualisation, distribution fitting, hypothesis testing,
regression modelling, and a forecast for when India's national EV share crosses the 10%,
20%, and 30% thresholds. Full methodology, results, and interpretations are in
`EV_Analysis.ipynb`.

## Repository Structure

```
.
├── EV_Analysis.ipynb       # Main notebook — run this
├── DataSet1/               # Raw Excel files, fuel-type wise (2014–2024)
├── DataSet2/               # Raw Excel files, state-wise EV (2019–2024)
├── DataSet1.csv            # Cleaned Dataset 1 (pre-generated)
├── DataSet2.csv            # Cleaned Dataset 2 (pre-generated)
├── Project_Proposal.pdf    # Initial proposal with problem statement and planned approach
├── requirements.txt
└── README.md
```

## Setup and Usage

```bash
git clone https://github.com/YOUR_USERNAME/india-ev-transition-analysis.git
cd india-ev-transition-analysis

pip install -r requirements.txt

jupyter notebook EV_Analysis.ipynb
```

The cleaned CSV files are already included, so you can run the notebook directly
without re-running the data cleaning cells. If you do want to regenerate them from
the raw Excel files, just run Section 1 of the notebook first.
