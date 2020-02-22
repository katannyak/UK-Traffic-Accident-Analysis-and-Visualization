# UK Traffic Accident Analysis and Visualization
<img align="right" height="200" src="https://www.shareicon.net/data/128x128/2015/12/27/693941_transport_512x512.png">

## Project description
As a part of a [Data and Visual Analytics](https://poloclub.github.io/cse6242-2019fall-online/) course, the goal of this group project was to extract novel insights and create a useful application from a large dataset. To this end, we analyzed the [UK Road Traffic Accident](https://www.kaggle.com/daveianhickey/2000-16-traffic-flow-england-scotland-wales/version/8) data set, UK air pollution data, and weather forecast information, to:
  * create an online tool to predict traffic accident risk so that users can make informed decision about their traveling route and,
  * conduct detailed analysis of the data and create visuals to communicate our findings to the public.

Our [online tool](https://kteo7.pythonanywhere.com/interaction) provides an interactive dashboard that allows users to enter their start and end locations in London and date and time of travel. The app will then call [Google maps API](https://cloud.google.com/maps-platform/) for route planning and a weather API, [Darksky](https://darksky.net/dev), for weather forecast data. These data will then be fed into our traffic accident prediction model and the map will update with hazard icons displayed at accident prone hotspots along the entered route. The app uses machine learning models for predictions. The web application was built using a Python Flask framework. As an example, the screenshot below shows three particularly bad hotsopts for potential traffic accidents enroute from the zoo to the Royal Observatory on a Friday afternoon.

<img align="center" height="500" src="https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/blob/master/data_viz/interactive_tool_screenshot.png">

The website also describes our [exploratory analysis and visualization](https://kteo7.pythonanywhere.com/exploration) of the data, including our methodology, description of algorithms developed, analysis and visualization of the data. For example, the choropleth map below shows which London boroughs have the highest (Westminster, dark purple) to lowest (Kingston Upon Thames, light blue) rate of traffic accidents. 

<img align="center" height="550" src="https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/blob/master/data_viz/choropleth_screenshot.png">

A nice description of this project was written by my colleauge Meraldo Antonio in this [article](https://towardsdatascience.com/live-prediction-of-traffic-accident-risks-using-machine-learning-and-google-maps-d2eeffb9389e).


## Directories
#### [`docs`](https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/tree/master/docs)
Contains our final report, a nice infographic for this project, and links to data sources.

#### [`code`](https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/tree/master/code)
Python code and data sets, e.g. traffic accident, atmospheric pollution, weather forcaste, and policitical sentiment data, used to create the model to predict traffic accident probabilities.

#### [`data_viz`](https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/tree/master/data_viz)
Python code for our data visualization analysis of UK traffic accidents.

#### [`app`](https://github.com/katannyak/UK-Traffic-Accident-Analysis-and-Visualization/tree/master/app)
Our website was built using Python Flask. Related Flask and html files can be found here.

