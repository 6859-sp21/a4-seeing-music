# 6.859 A4: Seeing Music

## Team Members
- Rachael Fuchs (rfuchs)
- Alizée Schoen (amschoen)
- Claire Yin (yinc)

## Dataset

We used a [kaggle Spotify dataset](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks) which consists of over 160k songs dating back to 1920.

## Design Decisions
First and foremost, we performed exploratory data analysis to explore different variables from the dataset. From this, we found that the large number of variables would make it hard to visualize all of the data at once. We chose selective visualizations that can focus in on a subset of the data. The dual-page style visualization helps us with this. On the first page, we have bubble graphs. We chose bubble graphs because popularity is a relative value, which can be depicted with circle sizes for easy user understanding and comparison.

On the artists page, we thought it would be most useful to see songs in relation to each of the artists. A lollipop chart was best to show a timeline of songs. Bar charts are a great way to depict all of the different song attributes, and even resemble music volume bars. We chose to exclude certain data that was inconsistent, such as the genre of each artist. However, this definitely also excluded some potentially interesting information from our visualization.

We decided on making our visualization rather exploratory for the user, than telling a story. This decision was made because there is a lot of important information about each song that we wanted to show. The dataset however did not contain any information about song albums, song backstory, and the genres for each song were very inconsistent, which is why our visualization doesn't show any of these.

Overall, having the embedded graphs that can be reached through clicks helps lead users through the different components of the visualization. The interactivity that allows users to vary year, the number of top artists and songs, and the number of songs on the artists page, allows for more user engagement.


## Overview of Development Process
An overview of your development process. Describe how the work was split among the team members. Include a commentary on the development process, including answers to the following questions: Roughly how much time did you spend developing your application (in people-hours)? What aspects took the most time?

We began by outlining our visualization based on tasks to be completed. We tried to split the work as equally as possible, with each person taking the reigns on a section of the visualization: Rachael led the development of the artists page, while Alizée and Claire led the development of the front page. 

Overall, developing our application took at least 20hr per person. The beginning of the development process involved a lot of familiarizing with the data and the charts we utilized. As we continued to build the application, we ran into random obstacles such as parsing the data, wrapping text in each bubble, adapting each bubble's text to its size, etc. Overcoming many of these small obstacles required a lot of time.
