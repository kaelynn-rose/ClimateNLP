# Exploring Climate Change Topics over Time with NLP & Machine Learning

## Introduction


## Data

For this project, I use The GDELT Project Exploring Climate Change Narratives On Television News 2009-2020 dataset (available here: https://blog.gdeltproject.org/a-new-dataset-for-exploring-climate-change-narratives-on-television-news-2009-2020/). This dataset contains 94,858 text clips from television news programs taken from the Internet Archive's Television News Archive, on BBC News, CNN, Fox News, and MSNBC stations. To be selected for this dataset, the clips had to contain one or more of the following phrases:

* 'climate change'
* 'global warming'
* 'climate crisis'
* 'greenhouse gas'
* 'greenhouse gases'
* 'carbon tax'

The CNN, Fox News, and MSNBC clips are from 2009-2020, and the BBC News clips are from 2017-2020. The dataset consists of 417 csv files, which I combined into a single dataframe during pre-processing. The combined dataframe had the following 7 features:

* URL (URL to the Archive's website to view the specific clip)
* MatchDateTime (the exact date and time of the mention)
* Station name
* Show (which show on the station the phrase was mentioned during)
* IAShowID (unique ID for each show with date and time of broadcast)
* IAPreviewThumb (thumbnail clip from the television program)
* Snippet (15 second clips, each containing a climate phrase mention)

## Data Cleaning


## NLP 


## Modeling


## Conclusions
