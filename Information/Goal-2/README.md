# Information: Goal 2

**“I would like to get more confident and do nice data visualizations (with python if possible)”**. 
 * **Background**: I have some experience with maps and plots, specially with GIS softwares like ArcGIS or QGIS. I have not much experience with maps and plots in Python nor ArcGIS Online.  
 * **How?** I will analyse the twitter and weather datasets and try to find patterns and correlations. I will represent the results in plots and some maps elaborated with python.
 
## Results
I ended up doing a lot of the cartographic work from the different analysis.

* **Python**
  * In Python I mostly did graphs and plot visualizations, however I also tried to do some simple maps. 
  
* **QGIS**
  * In QGIS, firstly, I read the output CSV files from the pre-processing and cleaning to geolocalize all the tweets in order to analyse them.
  <details>
    <summary><b>QGIS Maps</b> (click to expand)</summary>
 
  <!-- toc -->
  |                  Title                 |  Map  | Elaboration                                            |
  |:---------------------------------------:|:-------:| ----------------------------------------------------------------- |
  |Total tweets by Hexagonal Grid  |[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/Tweets_Hex_Grid_2d.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/Tweets_Hex_Grid_2d.png)[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/Tweets_Hex_Grid.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/Tweets_Hex_Grid.png)| Hexagonal Grid elaborated with MMQIS plugin. Then, "Count points in Polygon". 3D visualization elaborated with Qgis2threejs. |
  |Tweets by Building |[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/TweetsByBuilding2.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/TweetsByBuilding2.png)[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/TweetsBuildings2.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/TweetsBuildings2.png)|Queried the buildings from QuickOSM plugin. Then, "Count points in Polygon. Used CartoDbDarkMatter background and inversed Viridis color ramp |
  |Positive and Negative Tweets by Land Use Type |[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/LanduseType_Tweets.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/LanduseType_Tweets.png)|Downloaded the land use types from [Amsterdam Open Data](https://data.amsterdam.nl/), then I used the tool "Join Attributes by Location" with the tweet points.|
  |Positive and Negative Tweets Clusters|[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/positive_tweets_cluster.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/positive_tweets_cluster.png) [<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/negative_tweets_cluster.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/negative_tweets_cluster.png)|To do this map, I created an squared/rectagonal grid over the tweets area. Then, I counted the points in polygons and I created centroids from the grid squares. I used the size assistant to use the flannery scale method. Inspired by [this](https://geolabs.wordpress.com/2016/03/16/how-to-count-overlapping-points-in-qgis-cluster-point-map/).|
  <!-- tocstop -->
  
  </details>
  
* **ArcGIS Pro and ArcGIS Online**
  * Since we wanted to present our project in an [ArcGIS StoryMap](https://storymaps.arcgis.com/stories/9af24266f96e42e4aae1daf34ad4ac3e) that included cartographical visualizations, I thought it would be a good oportunity to practise with ArcGIS Pro and ArcGIS Online. 
  <details>
    <summary><b>ArcGIS Maps</b> (click to expand)</summary>
 
  <!-- toc -->
  |                  Title                 | Elaboration                                            |
  |:---------------------------------------:| ----------------------------------------------------------------- |
  |[Tweets by Land Use Type](https://arcg.is/1n15P1)| The same as in QGis|
  |[Positive and Negative Comparison](https://wur-girs.maps.arcgis.com/apps/StorytellingSwipe/index.html?appid=b6473b63861f447e904e19bb3c4da0eb)| Plotting the positive and negative tweets. They are also divided by "Inside" or "Outside" (I selected them by location and created a new layer)|
  |[Positive and Negative, Weather Geo-Means Comparison](https://wur-girs.maps.arcgis.com/home/item.html?id=ebe8f19f73a74ef48e7cd5c382f82ee4)|In ArcGIS-Pro I created the means (and also median) using Mean Center and Median center, from spatial statistics|
  |[Clusters and Outliers](https://arcg.is/0DqyS4)|Made this spatial analysis using the Optimized Outlier Analysis|
  |[Tweets by Hex-grid](https://arcg.is/1LWyCP)|Data processed in QGis, exported to ArcGIS Pro|
  |[Amsterdam Landuse Types](https://arcg.is/0DqyS4)|Data from [Amsterdam Open Data](https://data.amsterdam.nl/)|

  <!-- tocstop -->
  
  </details>

