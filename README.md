# RavenPack-Data-Aggregation
The dataset contains 11 columns: 
- entity_name	exportergroups
- year
- N_event_sentiment_negative
    - this contains the number of negative event sentiment scores for each company
- N_event_sentiment_positive
  - this contains the number of positive event sentiment scores for each company
- N_event_sentiment_neutral
  - this contains the number of neutral (value = 0) event sentiment scores for each company; note that this excludes data where no sentiment score is present, and only contains the number of sentiment scores that are 0
- N_composite_sentiment_negative
- N_composite_sentiment_positive
- N_composite_sentiment_neutral
- Av_event_score
  - the average event sentiment score per year, calculated by (sum of all event sentiment scores) / (number of event sentiment scores). Note that the calculation does not take into account empty cells for the the total number of scores.
- Av_composite_score

# Timestamp of RavenPack Data
