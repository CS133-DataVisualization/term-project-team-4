# If running in Google Colab

Download the CS133_F25_Team4_Project_Notebook.ipynb file to your desktop, and upload it to your Google Colab account. If the file is unable to be uploaded to Google Colab for some reason, make a copy of the Colab document at this link: https://colab.research.google.com/drive/1vQol3pnQeuj8wORly5eA8Dz7HU9vHXf_?authuser=1

Before running the Google Colab document, please create a code cell at the top and run the following command:

```
!pip install jupyter_bokeh
```
This will install all of the widgets needed to run the interactive portion of the notebook.

For Google Colab, please download the datasets below: 

```
regular_season_box_scores_2010_2024_part_1.csv
regular_season_box_scores_2010_2024_part_2.csv
regular_season_box_scores_2010_2024_part_3.csv
regular_season_totals_2010_2024.csv
```
These should be in the repo already. After this, put it somewhere in your Google Drive. Modify the file paths in the second cell to wherever you have them organized in your Google Drive. How to modify the file path is detailed on Google Colab. 

After that, the document should run! 

# If running on a native kernel / Native Desktop

Clone this repo to your device, and open up The CS133_F25_Team4_Project_Notebook.ipynb file in whatever environment you wish that can open .ipynb files.

Make sure your kernel has the following modules installed by running this command after activating your kernel or on your device:

```
pip install numpy pandas plotly panel matplotlib seaborn scikit-learn.
```

After that is installed, in the dataset import cell, comment out the Google Drive cell and uncomment the section under "Native Code". 
Download the following files from the repo:

```
regular_season_box_scores_2010_2024_part_1.csv
regular_season_box_scores_2010_2024_part_2.csv
regular_season_box_scores_2010_2024_part_3.csv
regular_season_totals_2010_2024.csv
```

For these files to be seen, make sure they are in the same subfolder as the notebook file when running it. After that, the file should run!
