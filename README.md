# README

## DATASET
That dataset can be found on this Google Drive [link](https://drive.google.com/drive/folders/11aW_fpXjA-O51uv3xYY3xj6NWGh1VYh_?usp=sharing).



### SUMMARY:
The dataset was created by crawling 13 subreddits from [reddit](www.reddit.com) to collect a total of 17159 posts and corresponding titles. Each subreddit was then associated to a class label as listed below:


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
1. **title:** The text in each title.
1. **post:** The text in each corresponding post. 
1. **class_name:** The class provided by us.
1. **class_id:** A unique ID used for each type of class:

| class_name    | class_id      |
| ------------- |:-------------:|
| adhd          | 0             |
| anxiety       | 1             |
| bipolar       | 2             |
| depression    | 3             |
| ptsd          | 4             |
| none          | 5             |


### DATASPLIT:
3 different kinds of .csv files were generated. The ID, class_name and class_id fields were common for each of these files:
- **both_*.csv:** Contains both posts and titles.
- **posts_*.csv:** Contains only posts.
- **titles_*.csv:** Contains only titles.

These 3 CSVs were further split into train, test and validation sets:
- ***_train.csv:** Training dataset.
- ***_val.csv:** Validation dataset.
- ***_test.csv:** Test dataset.