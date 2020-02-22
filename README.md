# UK Traffic Accident Analysis and Visualization
<img align="right" height="200" src="https://www.shareicon.net/data/128x128/2015/12/27/693941_transport_512x512.png">

## Project description
As apart of a [Data and Visual Analytics](https://poloclub.github.io/cse6242-2019fall-online/) course, the goal of this group project was to extract novel insights and create useful applications from a large dataset. To this end, we analyzed the [UK Road Traffic Accident](https://www.kaggle.com/daveianhickey/2000-16-traffic-flow-england-scotland-wales/version/8) data set, UK air pollution data, and weather forecast information, to:
  * create an online tool to predict traffic accident risk so that users can make informed decision about their traveling route and,
  * conducted detailed analysis of past data and create visuals to communicate our findings to the public.



Our web interface contains two parts, namely exploration and interaction. In the exploration part, we presents our research methodology, algorithm used, analysis and visualization of the data. In the interaction part, user can make use of an interactive dashboard to predict the probability of RTA in their chosen routes.

The app uses machine learning models for predictions. User will have to enter a date and time, an origin and travel destination. The app will then call [Google maps API](https://cloud.google.com/maps-platform/) for route planning and a weather API, [Darksky](https://darksky.net/dev)
for weather forecasts. These data will then be fed into the model and probability of RTA occurring in user's route will be displayed on the map as hazard icons.

The web application is built using Python Flask framework and is currently being hosted in Pythonanywhere, [here](http://kteo7.pythonanywhere.com/home).

### Data Visualization
<img align="right" height="244" src="https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/blob/master/data_viz/heatmap_day_vs_hour.png">


A nice description of this project is provided in this [article](https://towardsdatascience.com/live-prediction-of-traffic-accident-risks-using-machine-learning-and-google-maps-d2eeffb9389e) written by colleauge Meraldo Antonio.

Data used in this project was obtained from [Kaggle](https://www.kaggle.com/daveianhickey/2000-16-traffic-flow-england-scotland-wales/version/8)










## Directories
#### [`docs`](https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/tree/master/docs)
Contains our final report, a nice infographic for this project, and links to data sources.

#### [`code`](https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/tree/master/code)
Python code and data sets, e.g. traffic accident, atmospheric pollution, weather forcaste, and policitical sentiment data, used to create the regression model to predict traffic accident probabilities.

#### [`data_viz`](https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/tree/master/data_viz)
Python code for our data visualization analysis of UK traffic accidents.

#### [`app`](https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/tree/master/app)
Our website was built using Python Flask. Related Flask and html files can be found here.

