# chlorophyll.github.io

## Gas Emission vs Chlorophyll Concentration

- by Team Chlorophyll: Zarreen Naowal Reza and Noah Sealy, for NASA SpaceApps Hackathon, October 2020

### Our Mission

If there's no chlorophyll, there's no life.

As the October 2020 Nasa SpaceApps Hackathon opened, Team Chlorophyll decided to devote their project and interest in data science to telling a story.
This story's main character is not an individual we see everyday; not one often mentioned on the news, nor one commonly tagged on social media; you'll seldom find discussions of it even in classrooms at universities.
This story's main character cannot even speak.

Yet its existence is so vital to the wellbeing and biodiversity of many of the World's oceans that one must stop and wonder how many resources are going into protecting it, and what must be done in order to help it, in what could very well be its darkest hour yet.
The main character of this story is known as Phytoplankton. Phytoplankton are a key nessecity in the health of oceans, which contribute to a large portion of the World's biodiversity.
NASA claims Phytoplankton to have a huge role in the food chains of many living creatures in bodies of water. They are able to grow with sunlight and chlorophyll.
Chlorophyll can be recorded through colour imagery, as its presence is indicated by the color green in bodies of water.
In order to show how climate change is changing the concentration of chlorophyll in bodies of water, we aim to model the rise of greenhouse gases such as CO2 as well as chlorophyll concentration in order to show a correlation between the two.
Our question of focus is as follows:

Will the chlorophyll concentration in specific bodies of water reduce with the evergrowing amount of gases such as CO2 and NO increase in the atmosphere?
The following sections discuss the results we found, how we found them, and what our plan moving forward is.

Throughout this web page, we will show you how Team Chlorophyll has begun processing data which aims to show the changing the concentration of chlorophyll in bodies of water.

We hope to not just share this story with you, but also make you a part of it; the environment has become a fragile whisper compared to the fierce shout it used to be, and it is everyones duty to do their part in helping the environment recover to its former glory
If we do not start taking this issue more and more seriously we will be nothing, because remember...
If there's no chlorophyll, there's no life.

### Dataset and Preprocessing

Although this website is developped with HTML, the majority of our code can be found in a Jupyter Notebook, which is a file that compiled and organizes Python code.
The code and images that follow are all from the Jupyter Notebook file.
We used the Pandas library in order to import and organize the data sets.
The datasets we used were SCISAT and the NOAA Ocean Color dataset.

In this part we did some data pre-processing to merge different gas data into one single file mapped by date, latitude and longitude.
Photo of the Pandas Dataset Import


### Methodology
First we analyzed the SCISAT data and NOAA data to observe the correlations visually. Next, we applied a Machine Learning model called Logistic Regression in order to predict the future trends of the correlation between gas emission and ocean color. Due to time limitation, we were not able to obtain the final model. It is part of our future work to get a perfect ML model and deploy it to our web application.

We showed that different gas concentration over the Arctic and Antarctica for past one years. Alongside, we show the chlorophyll distribution in the same region during the same time of the year.

<img align="right" width="50%" src="https://github.com/noahsealy/NASA-SpaceApps-Hackathon-2020-Project/blob/main/images/CH4.png" />
<img align="right" width="50%" src="https://github.com/noahsealy/NASA-SpaceApps-Hackathon-2020-Project/blob/main/images/CO.png" />
<img align="right" width="50%" src="https://github.com/noahsealy/NASA-SpaceApps-Hackathon-2020-Project/blob/main/images/H20.png" />
<img align="right" width="50%" src="https://github.com/noahsealy/NASA-SpaceApps-Hackathon-2020-Project/blob/main/images/N2.png" />
<img align="right" width="50%" src="https://github.com/noahsealy/NASA-SpaceApps-Hackathon-2020-Project/blob/main/images/NO2.png" />
<img align="right" width="50%" src="https://github.com/noahsealy/NASA-SpaceApps-Hackathon-2020-Project/blob/main/images/O3.png" />



### Our Goals
Although the Hackathon is over after 48 hours, Team Chlorophyll has only just begun.

### Future Work
For the future, Team Chlorophyll would like to aim to find more datasets relating to effects that climate change may have on the World's oceans. This may include data relating from checmical levels to species populations.
With this tentative data we would like to continue to use data science related models such as solving regressions to try and find trends that may result in strong correlations.

### The Dashboard
As far as the website goes, we would like to expand it out quite a bit. We believe that adding more interactive components may be key in the engagement of users. This may include:
Sliding windows which show chlorophyll and green house gas concentrations on a world map over time.
Add aditional prediction models on the data.
Add more entries of datasets, such as mentioned above.
This webpage is truly just a prototype of where we want this to go, the end goal being a fully interactive dashboard!

### The Audience
It is also important to spread this data! We wish to share our findings with great masses of people, ranging from researchers to fisheries; anyone who is interested in the ocean and all of its greatness!
Lastly, we want to stay dedicated to the fight against climate change and global warming, and continue to use the data to make a difference.

### Our Thanks
On behalf of Team Chlorophyll, we would like to close this by thanking everyone involved in running the Hackathon this weekend.
We've learning a ton about data and the environment, and felt that this project was an amazing opportunity to be apart of!
We are very grateful for everyone who was involved, and hope to be able to participate in the next one. Thank you.
