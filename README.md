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



## INTERESTING RESULTS
| Platform      | Post                                            | Predicted Class |
| ------------- |:------------------------------------------------|:---------------:|
| Reddit        | most people able to be productive and functional when their basic needs are fulfilled... so do i! but what different is what i need is fun and exciting stuffs (or my meds) for me to be able to being productive and ""functional"" (or my brain will be potato). people can't go on if they are hungry, i can still go on all day all night if i have my squishies or after hearing a good song in spotify which gives me my spurts of dopamines!            | adhd            |
| Reddit        | like the real laugh, from the heart... and its usually about something stupid but it feel so good and you stop and think of how long its been since that happened, and how you cant imagine that people are laughing and feeling like this all the time? when i get where i'm going i'm going to laugh and smile like that every day, and its going to be amazing.            | depression            |
| Reddit        | hello! i've had insomnia as early as age 7. at this point, my ability to fall and/or stay asleep is so difficult that i am taking sleep when i can. it's not the same as when you sleep a lot because you're depressed. it's just that if i feel sleepy at 5:30 pm, then i'm going to grab that opportunity, because if i don't and then get a second wind, then i may be awake until 6 am. also, sometimes these bouts of sleepiness are impossible to ignore. i'm going to fall asleep, it's happening, it has to happen! it's that or hardly any sleep at all. obviously this affects my life, but i'm still able to maintain attendance at school and work. because of this, i've kinda rationalized sleeping this way. i've abided by all the sleep hygiene rules and still no cigar. so this is what i'm settling at. does anyone else do this or feel this way?           | bipolar            |
| Reddit        | i'm writing a simple computer program that changes the color of the screen based on the mouse's position on the screen and the current minute expressed in milliseconds. we'll call these three values the parameters. when we divide the maximum value of the parameters by 256, we get a 'unit' of color. we can then multiply the actual value of a parameter by it's corresponding color unit to find that colors intensity, where 0 is no intensity and 255 is maximum intensity. this 0 - 255 range is our number line. the problem i'm running into is that when the next minute starts, whichever color that parameter is representing will flip from maximum intensity to no intensity. i would prefer instead that it 'bounce' off of the end of the number line and start moving back. is it possible to accomplish that mathematically, without too much computer logic? this is the program, if you're curious           | none            |
| Twitter        | When people have asked me in the past to describe what ADHD feels like I get into details about how it impacts my life every day but I always add that for me that ADHD has caused me a great deal of emotional pain. It's a frustrating, infuriating disorder.| adhd            |
| Twitter        | One of the challenges for me is in order to focus on something like writing, unless I have the adrenaline that comes with not wanting to get scooped, I have to really shut out everything. But people don't understand that I can't do a back and forth when I'm in that zone.  | adhd            |
| Twitter        | Traumatic events can occur in any work environment and anyone can suffer from a post-traumatic stress reaction.    | ptsd            |
| Twitter        | I was that person that couldn't get out bed, unmotivated, hurting and watching time just slip away.                | depression            |
| Twitter        | I have AWFUL anxiety when it comes to driving and there's been many times I've just cried at the wheel. Today may not look like much for a lot of people, but it was a huge leap for .                | anxiety            |
| Twitter        | I really truly feel for Kim Kardashian. Bipolar disorder is so confusing and so exhausting to deal with & when a person you love is having a break it is very hard to navigate. She has to do what’s best for her kids & her even if it breaks her heart in the meanwhile.                | bipolar            |
| Twitter        | From this week's issue: Google AI announced the release of TensorFlow 3D, a set of training and evaluation pipelines for state-of-the-art 3D semantic segmentation, object detection and instance segmentation, with support for distributed training.                | none            |
| Facebook        | It is like being scared and tired at the same time. It's the fear of failure but no urge to be productive. It's wanting friends but hate socializing. It's wanting to be alone but not wanting to be lonely. It's caring about everything then caring about nothing. It's feeling everything at once then feeling paralyzingly numb.                | depression            |
| Facebook        | i'm anxious about going back to work. i haven't been to work since my mom passed new year's eve and i'm so nervous. i feel like one of my coworkers is going to be mad at me still because i didn't file the last few days before i left because i had been the only one filing and wanted her help. she told my manager that i just wasn't doing it and she was upset with me about it. i'm nervous she'll still be upset with me and i have to see her today. any advice or kind words would be appreciated.                | anxiety            |
| Facebook        | I was just wondering if it's normal to experience lapses of time while going through ptsd? It's been almost 3 years and it just doesn't feel like it and it's really stressing me out coz I feel like I missed out on so much and I'm not sure where I've been at???                | ptsd            |
| Facebook        | I'm looking for a 2 bhk fully furnished flat in a society/gated society.I have to move in from Mid of March.                | none            |
| Tumblr          | Having an anxiety disorder is like that moment where your chair almost tips or you miss a step going down the stairs but never stops.                | anxiety            |
| Tumblr          | Wow it would be great to arrive to places on time and have a basic grip on impulse control!!!social skills would be cool too but you can't always get what you want i guess!                | adhd            |