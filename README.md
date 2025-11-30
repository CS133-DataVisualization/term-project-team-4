# If running in Google Colab

Before running the Google Colab document, please create a code cell on top, and run the following command:

```
!pip install jupyter_bokeh
```
This will install all of the widgets needed to run the interact portion of the notebook

For Google Colab, please downloaded the datasets below: 

```
regular_season_box_scores_2010_2024_part_1.csv
regular_season_box_scores_2010_2024_part_2.csv
regular_season_box_scores_2010_2024_part_3.csv
regular_season_totals_2010_2024.csv
```

These should be in the repo already. After this, put it somewhere in your Google Drive. Modify the file paths to wherever you have them organized in your google drive. How to modify the file path is detailed on the Google Colab. 

After that, the document should be able to run! 

# If running on a native kernel

Make sure your kernel has the following modules installed by running this command after activating your kernel or on your device:
pip install numpy pandas plotly panel matplotlib seaborn scikit-learn

After that is installed, on the dataset import cell, comment out the google drive cell and uncomment the section under "Native Code". 
Download the following files from the repo:

```
regular_season_box_scores_2010_2024_part_1.csv
regular_season_box_scores_2010_2024_part_2.csv
regular_season_box_scores_2010_2024_part_3.csv
regular_season_totals_2010_2024.csv
```


For these files to be seen, make sure they are in the same subfolder as the notebook file when running it. After that, the file should be able to be run!
