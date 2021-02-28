# README

## DATASET
That dataset can be found on the following GOOGLE-DRIVE link:
https://drive.google.com/drive/folders/11aW_fpXjA-O51uv3xYY3xj6NWGh1VYh_?usp=sharing


### SUMMARY:
The dataset was created by crawling various subreddits from www.reddit.com. It contains a total of 17159 posts and corresponding titles. 13 different subreddits were crawled to extract posts and titles which were then classified under the following classes:


| Subreddit     | Class         |
| ------------- |:-------------:|
| adhd          | adhd          |
| anxiety       | anxiety       |
| bipolar       | bipolar       |
| depression    | depression    |
| ptsd          | ptsd          |
| datasets      | none          |
| english       | none          |
| mathematics   | none          |
| india         | none          |
| music         | none          |
| politics      | none          |
| science       | none          |
| travel        | none          |


### FIELDS:
The dataset consists of four columns:
1. **ID:** A uniquely generated ID used to distinguish each record.
1. **title::** The text in each title.
1. **post:** The text in each corresponding post. 
1. **class_name:** The class provided by us.
1. **class_id:** A unique ID used for each type of class.

### DATASPLIT:
3 different kinds of .csv files were generated:
- **both_*.csv:** Contains both posts and titles.
- **posts_*.csv:** Contains only posts.
- **titles_*.csv:** Contains only titles.

These 3 CSVs were further split into train, test and validation sets:
- ***_train.csv:** Training dataset.
- ***_val.csv:** Validation dataset.
- ***_test.csv:** Test dataset.

