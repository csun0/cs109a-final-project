# Mortality Prediction & Interpretation

**Video**: https://youtu.be/BL8n3NDqzIs

By Christie Hung, Raymond So, Chris Sun, Erica Wu

Final Project for Harvard's CS 109a (Fall 2020) 

## Data Sources: 
Our dataset comes from [CrunchBase](https://public.tableau.com/s/resources?qt-overview_resources=1#qt-overview_resources) - it contains information for nearly 50,000 companies: what markets they operate in, when they were founded, where they're based, how many funding rounds they had, who invested, by whom they were acquired, etc. We also used data from [Simple Maps](https://simplemaps.com/) to get latitude and longitude coordinates for cities. Information about different companies was taken from Wikipedia articles, [TechCrunch](https://techcrunch.com/2013/12/14/crunchbase-reveals-the-average-successful-startup-raises-41m-exits-at-242-9m/) articles, and [miscellaneous articles](https://www.investopedia.com/articles/personal-finance/102015/series-b-c-funding-what-it-all-means-and-how-it-works.asp).

## Directories:
- `css/`: contains our custom `style.css` and library CSS files

- `data/`: 
  - `clean/`: modified data sources 
  - `raw/`: raw csv files obtained from Crunchbase and Tableau
  - `scripts/`: Jupyter Notebooks used to perform EDA, clean data, modify CSVs, and create JSON files
  
- `img/`: miscellaneous images used throughout the website

- `index.html`: main html file 

- `js/`: contains js files - [`bootstrap-multiselect.js`](https://bbbootstrap.com/snippets/multiselect-dropdown-list-83601849), [`jquery.drawsvg.js`](http://leocs.me/jquery-drawsvg/),  and [`noframework.waypoints.js`](http://imakewebthings.com/waypoints/guides/getting-started/) are external; all other files are internal
  - `barVis.js`: bar chart visualization
  - `bootstrap-multiselect.js`:
  - `bubbleVis.js`: static bubble chart visualization
  - `chartPacking.js`: dynamic, zoomable chart packing visualization
  - `chooseVis.js`: epilogue visualization
  - `innovativeVis.js`: funding timeline visualization
  - `jquery.drawsvg.js`:
  - `legend.js`: reusable legend used in bubbleVis and chartPacking
  - `main.js`: main js file for loading data and visualizations
  - `mapVis.js`: map visualization
  - `noframework.waypoints.js`:
  - `scatterVis.js`: scatter plot visualization


