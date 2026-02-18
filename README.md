# FMATutorials

This report contains tutorials and examples explaining how to use the [Football Match Analysis](https://github.com/JohnComonitski/FootballMatchAnalysis) library and work with event & tracking data.

### Table of Contents
<!--TOC-->

- [Football Match Analysis](#footbal-match-analysis)
  - [Getting Started](#getting-started)
  - [Tutorials](#tutorials)
  - [Data Sources](#data-sources)
 
## Getting Started
1. Clone the repository

   ```shell
   git clone https://github.com/JohnComonitski/FMATutorials.git
   ```

2. Move to the project directory

   ```shell
   cd FMATutorials
   ```

3. Create and activate a Python
   [virtual environment](https://docs.python.org/3/library/venv.html#creating-virtual-environments).
   On GNU/Linux systems this is as easy as:

   ```shell
   python3 -m venv .venv
   . .venv/bin/activate
   # Work inside the environment.
   ```

4. Install the Python dependencies

   ```shell
   pip install -r requirements.txt
   ```

## Tutorials
...

## Data Sources
 - [Official Metrica Tracking & Event Data](https://github.com/metrica-sports/sample-data)
 - [Generate Your Own Tracking & Event Data](https://github.com/JohnComonitski/FootballTrackingDataGeneration)
  > [!NOTE]
  > Data should be added to the ./data directory and each match should be contained to its own directory in the following format.
  > ```
  > 📁 data
  >    📁 MATCH_ID
  >      📄 MATCH_ID_RawEventsData.csv
  >      📄 MATCH_ID_RawTrackingData_Away_Team.csv
  >      📄 MATCH_ID_RawTrackingData_Home_Team.csv
  > ```


