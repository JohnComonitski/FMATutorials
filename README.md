# Football Match Analysis Tutorials

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

5. Work through the `getting_started.ipynb` notebook to install the FMA library and download sample data. The tutorial notebooks in this repo require this library and data to run.
 

## Tutorials
📁 basics
> [1. Load Match](https://github.com/JohnComonitski/FMATutorials/blob/main/basics/1%20load%20match.ipynb)
 
> [2. Creating Plots](https://github.com/JohnComonitski/FMATutorials/blob/main/basics/2%20creating%20plots.ipynb)

> [3. Working With Events](https://github.com/JohnComonitski/FMATutorials/blob/main/basics/3%20working%20with%20events.ipynb)

> [4. Moments](https://github.com/JohnComonitski/FMATutorials/blob/main/basics/4%20moments.ipynb)
  
📁 spatial_analysis
> [1. Heat Maps](https://github.com/JohnComonitski/FMATutorials/blob/main/spatial_analysis/1%20heat%20maps.ipynb)

> [2. Zones](https://github.com/JohnComonitski/FMATutorials/blob/main/spatial_analysis/2%20zones.ipynb)

> [3. xG](https://github.com/JohnComonitski/FMATutorials/blob/main/spatial_analysis/3%20xg.ipynb)

> [3. xT](https://github.com/JohnComonitski/FMATutorials/blob/main/spatial_analysis/4%20xt.ipynb)

📁 event_analysis
> [1. Key passes](https://github.com/JohnComonitski/FMATutorials/blob/main/event_analysis/1%20key%20passes.ipynb)

> [2. One Twos](https://github.com/JohnComonitski/FMATutorials/blob/main/event_analysis/2%20one%20twos.ipynb)

> [3. Possessions Per Shot](https://github.com/JohnComonitski/FMATutorials/blob/main/event_analysis/3%20possessions%20per%20shot.ipynb)

> [4. Packing](https://github.com/JohnComonitski/FMATutorials/blob/main/event_analysis/4%20packing.ipynb)

📁 advanced_analysis
> [1. Pitch Control](https://github.com/JohnComonitski/FMATutorials/blob/main/advanced_models/1%20pitch%20control.ipynb)

> [2. Pass Probability](https://github.com/JohnComonitski/FMATutorials/blob/main/advanced_models/2%20pass%20probability.ipynb)

> [3. EPV](https://github.com/JohnComonitski/FMATutorials/blob/main/advanced_models/3%20epv.ipynb)

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


