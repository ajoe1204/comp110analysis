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

<img src="{{ site.baseurl }}/static/imgs/videos_hist.png" alt="Histogram of video answers" width="300"/>

## Conclusion

I predicted that people not studying computer science would vote higher on having pre-lecture videos, but after finding the averages of scores, non-majors actually voted lower on the videos. However, additional evaluations indicate that non-majors who find the course challenging do vote higher, as seen in the line graph's upward trend. The combined line graph with majors and non-majors also trends upward, but likely is because there is a significantly higher number of non-majors in teh course since the non-major chart remains relatively flat and even drops off a bit as students answered that the class was more difficult. As a result, my data indicates that pre-lecture videos would likely aid non-majors who find the course difficult -- not non-majors as a whole. 