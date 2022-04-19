# Digital Humanities 2022 - Analysis of Memes
## Fabian Schiller, Mathias Götz - Universität Regensburg

This GitHub Repo contains all data (corpus) collected during writing of  "A Diachronous Analysis of Memes - Reddit Memes since 2013" for the Digital Humanities Course of University of Regensburg.
Data was collected using the Pushbullet FastAPI. The Goal was to download the Top 1000 memes sorted by score from each half year between 2013 and 2021.

Folders:
======
JSon Response
---
All JSon API responses with all data returned by the API. Each half year consists of 10 JSon files.

Memes
---------
All downloaded memes as jpg/png file.

Original Dataset
--
The original CSV created when downloading, conatining all memes and metadata as well as the download_log.txt, containing information on how many memes could be ackquired successfully from each half year.

Datset
-
The processed Dataset, with added Google Cloud Transcription.
Full Dataset with all memes (memes_full.csv) as well as split into the half years.

 LIWC
 -
 LIWC Table analysis.
CSV Files for each half-year and full dataset. 

 Sentiment
 -
  Datasets with added sentiment value scores (+ Compound Values), as well as overall Sentiment per meme. Created using Vader-Sentiment.
 CSV Files for each half-year and full dataset. 
 
 Wordclouds
 -
 Wordclouds for each half-year as well as the full Dataset.
 
TermFrequency
-
Term-Frequency Table for the full Dataset in CSV Format.


