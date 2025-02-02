Please see summaries of my featured projects below. Click on a project's title to access it.
## [Project 1: Public Company Finder NLP](https://github.com/thclough/stochastic_matrix_calculator) 
* Crawled financial news site for articles about public companies and scraped over 30,000  articles using Selenium
* Cleaned, processed, and labeled data using custom algorithm
* Created bidirectional LSTM in Tensorflow/Keras with custom data loading, custom embedding layer to train certain embeddings on the fly, and custom loss function
* Achieved F1 metric of .818 during evaluation, error analysis indicated artificially low evaluation metric due to mislabeled data


## [Project 2: Stochastic Matrix Calculator](https://github.com/thclough/stochastic_matrix_calculator) 
#### in collaboration with [Alton Banushi](https://github.com/banushi-a)
* Automate common calculations and classfications for a given right stochastic matrix (see readme for list of calculations)
* Implemented pared-down Tarjan's Strongly Connected Components Algorithm to test if a stochastic matrix is ergodic
* Created short calculation that uses eigenvectors to produce the equilibrium distribution(s) of a stochastic matrix
* REPL user-interface for calculations

## [Project 3: Wartime Presidents Inaugural Addresses: NLP Analysis](https://github.com/thclough/inaugural_address_analysis)
* Processed text from selected inaugural addresses
* Generated word clouds for each speech
* Visualized sentiment scores for comparison among speeches
* Create Sankey diagram to show common usage of non-trivial words

<img src="preview_images/word_clouds.png" height=300 width=450 align="left"/>
<img src="preview_images/vocab_sankey.png" height=250 width=500/>

<br>

## [Project 4: Challenger Incident Analysis](https://github.com/thclough/challenger_incident_analysis)
* Calculated inverse distance-weighted temperatures from weather station data to investigate the *Challenger* Shuttle Disaster
* Visualized temperatures across the United States on a given day using numpy array meshgrids and overlaying on a US map
* Integrated visualizations into a story of the incident

<img src="preview_images/usa_temp.gif"/>
