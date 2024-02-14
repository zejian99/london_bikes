# London Bike Dataset Cleaning

This repository is used to show what I did in my data cleaning process for the London Bike Sharing Dataset from kaggle.

The link to the dataset can be found [here](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset?resource=download)!

## TLDR
1. I first downloaded the dataset from Kaggle (you can totally download using an API call), this can simply be done by doing so:

    **Notebook** environment:
    ```
    !kaggle datasets download -d hmavrodiev/london-bike-sharing-dataset
    ```

2. Then I loaded the dataset into a **Pandas** dataframe, thereafter did cleaning by renaming column names to more friendly ones, then changing the integer values of certain columns to strings for easier data visualization later on in [Tableau](https://www.tableau.com/).

3. Tableau visualization to be documented and pushed to the repository in future!