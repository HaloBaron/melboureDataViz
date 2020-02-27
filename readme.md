# 🗺 AI Real Estate Project
### Mason, Graeme, and Brandon

#### Here's what we need to have finished for the 1st of March.

- Python project finished.
- Presentation finished and submitted to Saqib. 

#### Presentation:
- Discuss the type of data in the data set.
- Each of us do a coding presentation.
- Interperet the results.


#### Code:
- At least 5 graphs.
- **Show** the outliers.
- Calculate the Standard Deviation.
- Reveal the data distribution.
- Display data in a pie chart. 
- Show number of property sales based on region.

 # 🐙 Installation 🐙
 - Navigate to a working directory on your confuser.
 
 - Open Terminal
 
 `git clone https://github.com/MasonLegere/melboureDataViz.git`
 
**You will also need to install Anaconda on your machine.**

`https://docs.anaconda.com/anaconda/install/`

### Here's a few notes on what we're using.

**This is from the tutorial in class.**

  ```python
  import pandas as pd`
  import numpy as np
  import matplotlib.pyplot as plt

  #This is just an example of reading a .csv file.
  df = pd.read_csv('animals.csv', delimiter = ',')
  df.sort_values(['animal'])
  df.plot(kind='bar')
  ```
