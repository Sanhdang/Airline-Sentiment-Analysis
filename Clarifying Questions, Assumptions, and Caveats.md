## Clarifying Questions, Assumptions, and Caveats

### **Clarifying Questions**
1. What is the primary business objective — improving overall customer satisfaction or targeting specific service aspects (e.g., baggage handling, in-flight experience)?
2. Should the sentiment analysis focus only on English reviews, or should multilingual reviews be translated and included?
3. Are there any specific competitor airlines of interest beyond Qantas Airways for deeper comparison?
4. Should the recommendations prioritize short-term quick wins or long-term strategic changes?
5. Is the analysis intended for internal operational improvements, public marketing, or both?

### **Assumptions**
- The dataset provided is representative of real-world customer experiences and includes a balanced mix of airlines, routes, and cabin types.
- Reviews are authentic and reflect genuine customer opinions without significant bias from fake or promotional reviews.
- Sentiment polarity calculated via VADER accurately captures the tone of customer reviews.
- LDA topic modeling results are meaningful and can be interpreted as representative themes.
- Airlines with more reviews have proportionally more reliable sentiment and topic scores.

### **Caveats**
- Sentiment scores are based on textual analysis and may not fully capture sarcasm, cultural nuances, or mixed sentiments in the same review.
- Airlines with fewer reviews may have skewed results that do not represent the general customer base.
- Topic modeling may group unrelated words together, requiring manual interpretation.
- Seasonal or event-driven anomalies (e.g., weather delays, pandemic restrictions) may influence results but are not isolated in this analysis.
- Recommendations are based on historical data and may not fully reflect future service conditions or customer expectations.
