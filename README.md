# Prediction Modelling for Hotel Ratings from Reviews, Reviewer Nationality and Hotel Location

## The Hypothesis
The goal is to determine if there is a relationship between keywords within a review and the rating a review recieves. What keywords specifically indicate a positive, negative and neutral review. Assumptions about the data is that all of it is honest reviews. Only keywords will be examined within the dataset potentially such as good, bad, negative. Null reviews, such as empty reviews or nonsensical reviews, or reviews that lack the key word will be initially ignored. Hotel Location and Reviewer Nationality will be examined as potential labels for prediction.

### Goals and Success Metrics
- Success will be measured in whether specific words link to successful ratings and negative ratings.
- Correlation between word and rating, location and nationality.

### Risks and Limitations
- Risks of the prediction really depend on the assumptions, that all the reviews are truthful. 
- Hotel is treated as constant, and as such, improvements due to reviews, external forces, and staff changes are largely ignored.
- Negative reviews could be due to a various reasons such as improper staff, incorrect room location. Initial predictive modeling will ignore such factors.
- Reviews could potentially affect subsequent reviews and this could affect relationships and predictions.
- External Factors such as weather, holidays, length of stay will be ignored. Times of year can be potentially simplified as a potential label such as months.

### Data Access
Data was obtained from Kaggle at the website, https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe