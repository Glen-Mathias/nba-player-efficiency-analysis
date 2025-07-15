# NBA Player Efficiency Analysis

A Jupyter notebook tool to calculate and visualize the efficiency of NBA players. You can either manually enter player stats or upload a CSV file in the required format. The notebook provides various visualizations and calculates custom efficiency metrics, including a Defensive Player of the Year (DPOY) score.

## Features
- Upload NBA player stats via CSV or manual entry
- Calculate custom player efficiency metrics
- Visualize stats with boxplots and pie charts
- Filter and analyze by position, team, or age bracket
- Defensive Player of the Year (DPOY) calculation

## Setup
1. **Clone the repository using SSH:**
   ```sh
   git clone git@github.com:yourusername/nba-player-efficiency-analysis.git
   cd nba-player-efficiency-analysis
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Open the notebook:**
   - In JupyterLab, VSCode, or Google Colab, open `Player_Efficiency_Updated.ipynb`.

## Usage
### 1. Upload Data
- Run the first cell to upload your NBA player stats CSV file. The CSV should have columns like `Player`, `Pos`, `Age`, `Tm`, `G`, `GS`, `MP`, `FG`, `FGA`, `FG%`, `3P`, `3PA`, `3P%`, `2P`, `2PA`, `2P%`, `eFG%`, `FT`, `FTA`, `FT%`, `ORB`, `DRB`, `TRB`, `AST`, `STL`, `BLK`, `TOV`, `PF`, `PTS`.

### 2. Manual Entry (Optional)
- Use the provided widgets to add a new player row manually if needed.

### 3. Analyze and Visualize
- The notebook will:
  - Calculate efficiency metrics
  - Show top players by custom efficiency
  - Visualize stats (boxplots, pie charts)
  - Filter by position, team, or age
  - Calculate and display DPOY candidates


## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

