# Facebook-Humans-or-Robot-Kaggle-Competition\
## Introduction
First Machine Learning Competition (Late Submission). <br> 
https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot
### Results 
Private score of 0.90641 <br>
Public score of 0.89041 <br>

Placing top 400 of global kaggle leaderboard

## Features Selected
'auction', 'device', 'time', 'country', 'ip', 'url', 'bids_per_auc', 'log_bids_per_auc', 'url_per_auc', 'log_url_per_auc', 'ips_per_auc', 'log_ips_per_auc', 'bids_per_dev', 'log_bids_per_dev', 'bids_per_country', 'log_bids_per_country', 'bids_per_ip', 'log_bids_per_ip', 'bids_per_url', 'log_bids_per_url', 'num_bids', 'log_num_bids', 'num_instant_counts', 'log_counts', 'response_difference', 'log_difference', 'change_ip_freq', 'log_change_ip_freq', 'countries_per_auc', 'log_countries_per_auc', 'bids_entropy_per_ip', 'log_bids_entropy_ip', 'bids_entropy_per_url', 'log_bids_entropy_url', 'bids_entropy_country', 'log_bids_entropy_country', 'log_url', 'log_auction', 'log_device', 'log_time', 'log_country', 'log_ip'

## Visualisations
Correlation Plot using Plotly

## Machine Learning Models
Used stratified K-Fold to compare the results of different models. CatBoostClassifier, RandomForestClassifier, ExtraTreesClassifier and AdaBoostClassifier. Decided to settle on RandomForestClassifier.

