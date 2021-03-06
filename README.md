# Oisín Ó Siochrú's Portfolio
Data science and related project portfolio

## M.E.Thesis: Big Data Analytics at JD.com: Evaluation of linear, nonlinear, and hybrid time series forecasting models.
* Completed an ME thesis in the applications of big data analytics in demand forecasting methods for e-commerce and online retailing using real world data of over 2.5 million customers.
* Implemented fundamental data analytical techniques such as data preprocessing, manipulation and structuring and developed and trained statistical ARIMA, Machine Learning Neural Network, and Hybrid ARIMA-Artifical Neural Network models using the refined training datasets.
* Manipulated and cleaned datasets for demographic segregation prior to forecasting retail demand. 
* Presented relevant findings and business implications based on model metric evaluation.

### Exmaple of model demand forecasts for top 5 product SKUs and 10th to 20th top product SKUs

<img src="{{ "/images/SARIMA%20Forecast%20SKU%20Results.png" | prepend: site.baseurl | prepend: site.url}}" alt="SARIMA%20Forecast%20SKU%20Results" width="35%" height="35%"/> <img src="{{ "/images/LSTM%20Forecast%20SKU%20Results.png" | prepend: site.baseurl | prepend: site.url}}" alt="LSTM%20Forecast%20SKU%20Results" width="35%" height="35%"/> 
<img src="{{ "/images/Rolling%20ARIMA%20Forecast%20SKU%20Results.png" | prepend: site.baseurl | prepend: site.url}}" alt="Rolling%20ARIMA%20Forecast%20SKU%20Results" width="35%" height="35%"/> <img src="{{ "/images/Hybrid%20ARIMA-ANN%20Forecast%20SKU%20Results.png" | prepend: site.baseurl | prepend: site.url}}" alt="Hybrid%20ARIMA-ANN%20Forecast%20SKU%20Results" width="35%" height="35%"/> 

## Personal Project 1: YELP API Dublin Pub Data Visualisation Project:
* Called and collected raw pub data from the greater Dublin area  using YELP Fusion API.
* Applied pre-processing steps (cleaning, filtering) to json data and parsed raw data to csv format.
* Presented summary statistics in pub review counts, ratings, and pricing ranges accross dublin both graphically and with mapping visualisation.

## Results of statistical summary 
<img src="{{ "/images/Generalvis.png" | prepend: site.baseurl | prepend: site.url}}" alt="/Generalvis" width="120%" height="120%"/>
<img src="{{ "/images/Boxplots.png" | prepend: site.baseurl | prepend: site.url}}" alt="/Boxplots" width="120%" height="120%"/>

## Mapping Visualisations 

### Zip codes by number of reviews 

<img src="{{ "/images/Review%20count.png" | prepend: site.baseurl | prepend: site.url}}" alt="/Review%20count" width="80%" height="80%"/>

### Zip codes by average rating

<img src="{{ "/images/Rating.png" | prepend: site.baseurl | prepend: site.url}}" alt="/Rating" width="80%" height="80%"/>


## Academic Project 1: Football API Data Visualisation Project: 
* Called and collected raw data from a public web football league API using Python and stored in JSON for subsequent analysis. 
* Applied pre-processing steps (cleaning, filtering & integration).
* Characterised and visualised with tables and graphic visualisations with various python packages for each step such as NumPy, Pandas, Matplotlib, Seaborn. 
* Summarised insights gained from analysis of the datasets.

## Academic Project 2: Webscraping Text Classification Project:
* Scraped a corpus of news stories through parsing a set of web page HTML and extracting specific text information. 
* Applied appropriate pre-processing steps to create a numeric representation of the documents suitable to train
* Performance binary classification and multi-class classification using KNN classification and 5 fold cross validation to classify news stories catagories from the set of extracted articles. 
* Used various python packages such as scikit-learn, itertools, beautiful soup.

### Results of Binary and Multi-class classification  

<img src="{{ "/images/Average%20accuracies%20of%20pair%20classification.png" | prepend: site.baseurl | prepend: site.url}}" alt="Average%20accuracies%20of%20pair%20classification" width="42%" height="42%"/> <img src="{{ "/images/Average%20fold%20accuracies%20vs%20KNN%20of%20pair%20classification.png" | prepend: site.baseurl | prepend: site.url}}" alt="Average%20fold%20accuracies%20vs%20KNN%20of%20pair%20classification" width="55%" height="55%"/>

---------------------------------------------------------------------------------------------------

<img src="{{ "/images/Confusion%20Matrix%20for%20Film%20and%20Business.png" | prepend: site.baseurl | prepend: site.url}}" alt="Confusion%20Matrix%20for%20Film%20and%20Business" width="43%" height="43%"/> <img src="{{ "/images/Confusion%20Matrix%20for%20Film%20and%20Sport.png" | prepend: site.baseurl | prepend: site.url}}" alt="Confusion%20Matrix%20for%20Film%20and%20Sport" width="42%" height="42%"/> <img src="{{ "/images/Confusion%20Matrix%20for%20Sport%20and%20Business.png" | prepend: site.baseurl | prepend: site.url}}" alt="Confusion%20Matrix%20for%20Sport%20and%20Business" width="40%" height="40%"/> 
<img src="{{ "/images/Confusion%20Matrix%20for%20all.png" | prepend: site.baseurl | prepend: site.url}}" alt="/images/Confusion%20Matrix%20for%20all"  width="40%" height="40%"/>
