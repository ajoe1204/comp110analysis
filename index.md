---
# Do not edit the text between these lines!
layout: default
---

# Alex Joe COMP110 EX09

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="{{ site.baseurl }}/static/imgs/logo.png" alt="My headshot" width="300"/>

## Premise

In this exercise, I investigated who pre-lecture videos would benefit most by analyzing how different groups of students voted on the question of videos. I combined the two classes' datasets to have an aggregated set of all COMP110 students' answers, not just those from Izzi or just Alyssa. Then, I assigned selected my questions of interest: "comp_major", "pace", "difficulty", "understanding", and "pre_lecture_videos." This created a new dataset with just those questions. Next, I used my helper function, average, to find the average score for each question for all students before separating them to find the averages for comp-studying students and non-comp-studying students. Then, I counted the total numbers each answer choice was chosen for the pre_lecture_videos question. Finally, I graphed a scatterplot of difficulty and pre_lecture_videos for people who are and aren't studying computer science. I also graphed line charts between difficulty and pre_lecture_videos to observe any correlation. Last, I made two histograms: one to observe the distribution of answers to pre_lecture_videos and the other to observe the distribution of answers about difficulty.

<img src="{{ site.baseurl }}/static/imgs/line_difficulty_videos.png" alt="Line charts of difficulty and video questions" width="300"/>

<img src="{{ site.baseurl }}/static/imgs/difficulty_all.png" alt="Histogram of video answers" width="300"/>

<img src="{{ site.baseurl }}/static/imgs/videos_hist.png" alt="Histogram of video answers" width="300"/>

## Conclusion

My analysis of the data does not entirely support my hypothesis that posting pre-lecture video would help people not studying computer science. After averaging the scores, computer science majors actually were more supportive of pre-lecture (5.529) that non-computer science majors (5.311), indicating that they would likely find them more useful. This contradicts my hypothesis that the non-majors would favor videos more and therefore find them more helpful, and the histogram and scatter plots reflect this trend. However, while the reasoning for my hypothesis may be wrong, some of my other analysis suggests that other groups would benefit from the videos. The other statistic I chose was difficulty, and looking at the line graphs, non-majors generally favor pre-lecture videos when they find the class harder. Furthermore, there was still a high average score for the videos among both people studying and not studying computer science, and 7 was the highest-chosen answer on the question, indicating that there is general support for pre-lecture videos. In conclusion, pre-class videos still would be a beneficial addition to COMP110, but they would not broadly target people who don't study computer science. Instead, they would likely aid non-majors who find the course difficult most.  

Adopting this proposal should not have any explicit negative effect for students on its own since videos (in my proposal) would be optional, meaning they will not take any extra time out of busy students' days. They would only be extra resources available to help those that wish to review content or get a head start. However, there may be a pitfall where students believe that the videos are the only things necessar for learning content, causing them to skip lectures to just watch the videos instead. This likely would cause some students to learn content less effectively since they are no longer attending class. Additionally, making pre-lecture videos would increaes the burden on instructors to make them, creating additional work for them outside of grading, lecturing, hosting office hours, and all other work. 

To further investigate the potential benefits of introducing pre-lecture videos, we differnetiate the COMP110 classes by offering pre-lecture videos for one section/instructor and compare grades and performance at the end of the year. This would involve taking a survey about how much students in the video-approved class watched the videos, drawing correlations between academic performace and interation with videos. However, this could raise concerns about fairness between classes. Instead, the instructors could introduce pre-lecture videos for everyone one year and see if scores increase for the entire class, comparing them to years past. While this would create less compelling data, such a test would satisfy issues of giving one class an advantage. 