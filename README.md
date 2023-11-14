# Eckomio
<img src="-project-image-0.png" width=50% height=50%>

# Problem & How it started
In terms of focus 2015 85% of the rental agreements contain a false number of living area which means that most of the people pay too much for their rent. A family member approached me with this idea to develop a tool which tracks the discrepancies and provide a first legal advice. From my previous projects I learned to first check for user acceptance before building a large application.

# Solution:
One of my roommates at this time was very good in web development so I brought him on board to build a first MVP. With a team of 3 people, we brainstormed with different approaches to the problem. Very quick we realized that it is very hard to capture the high variety of floor plans. In addition, there was no way to capture the room sizes in an automated way. The biggest question then was: are people willing to manually measure their apartment? Are people in general interested to legally go against their landlord?

# Technical Implementation:
In our technical screening phase, we explored a lot of possibilities: measuring with video, measuring with phone sensors, 3D visualization and so on. We soon realized that all the more advanced solutions could possibly make the measurement process way faster but this is definitely not a quick win. Therefore, we decided for a very basic application which acts more as guidance and the measurement has to be done manually.
During a "Weekend hackathon" we built a first prototype in Vue.js & Firebase which helps the user to find the discrepancies. I have never worked with this stack but was eager to learn something new. Users were able to register themself, add their apartment and then add rooms to this apartment. For each room the user needed to measure the room manually and enter the result into the app. After finishing the whole process, the user got immediately the result if the discrepancies are legally okay or not. All in all, the app was very clunky but we didn’t invest more time into it on purpose.
Deployment:
Our first idea was then to measure a few apartments of ourselves and friends. Very soon we saw some early red flags:
-	I measured my apartment and realized that there is actually a high discrepancy and I could sue my landlord. BUT: We had a good relationship with them and wanted to keep the good atmosphere (red flag no.1)
-	We asked friends if they could measure their apartment. Literally everyone was too lazy (red flag no. 2)
With this knowledge we still wanted to give it a try and would like to see how “real” people behave. We then went out and put flyers into the mail box of around 500 people. This resulted in some traffic to the landing page but only one person who registered but did measure the apartment.

# Lessons Learned:
I would more or less do the project the same way again. We didn’t invest too much time into the technical stuff and tried to capture the key hypothesis of potential customers. We soon realized the two red flags which were kind of a deal breaker for the whole project. It was still very fun to work with friends on such a topic. If I could do one thing differently I wouldn’t even start with any application and rather go from house to house and speak to people about this topic.
