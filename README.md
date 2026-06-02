# NBA Free Throw Analysis: 2018-19 Season

Statistical analysis exploring patterns in NBA free throw shooting using play-by-play data.

## Key Findings

**Sequential Performance** 
Players shoot **5.3% better** on their 2nd free throw (79.0%) compared to their 1st (73.7%), suggesting a "warm-up" effect.

**Home Court Advantage** 
No meaningful difference: Home 76.2% vs Away 76.1%. Free throws appear immune to crowd effects.

**Arena Effects** 
7% performance gap between best and worst arenas, potentially due to lighting, rim characteristics, and other environmental conditions.

**Game Context**
Free throw performance in 4th quarter decreases slightly (~2%). Score differential has minimal impact on performance. 

## Dataset

**Source:** [NBA Play-by-Play Data 2018-19 on Kaggle](https://www.kaggle.com/datasets/schmadam97/nba-playbyplay-data-20182019?select=NBA_PBP_2018-19.csv)

*Note: Dataset is too large for GitHub. Download from Kaggle and place in project directory.*

## Technologies

Python • pandas • matplotlib • numpy • Jupyter Notebook

## Setup

```bash
# Install dependencies
pip install pandas matplotlib numpy jupyter

# Download dataset from Kaggle link above

# Run analysis
jupyter notebook analysis.ipynb
```

## Project Structure

```
├── analysis.ipynb              # Main analysis notebook
├── NBA_PBP_2018-19.csv        # Data (download separately)
└── README.md
```

---

*Portfolio project analyzing NBA free throw patterns through descriptive statistics and visualization.*
