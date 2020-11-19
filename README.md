# Visualization Comprehension Scatterplots Dataset
A dataset for studying the effect of data size and pattern salience on general users' comprehension of visualization, especially the efficiency and accuracy of intermediate-level scatterplot tasks.

## File Structure
- `./formal experiment material`: This folder contains all materials for the formal experiment, which includes:

  - `./preliminary material/paticipant_answers`: This folder includes the answers of all 54 participants in the experiment.

  - `./preliminary material/processed_data (npy)`: This folder includes the processed .npy files. Each file contains the two dimensions we extracted from the raw .csv files.

  - `./preliminary material/raw_data (csv)`: This folder includes the raw .csv files we used to generate the test dataset. All the files in this folder are downloaded from Kaggle (https://www.kaggle.com/). The data in "7.csv" is used as the dataset for the training section.

  - `./preliminary material/scatterplots (png)`: This folder includes all scatterplots we used for the experiment.

  - `./preliminary material/task.json`: This file contains the questions we designed for each scatterplot in `./scatterplots (png)`.

- `./preliminary material`: This folder contains all visualization examples (18 subtypes) we collected for the preliminary study.
