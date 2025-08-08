# Airline-Sentiment-Analysis
A comprehensive data analysis of airline passenger reviews, including sentiment analysis, topic modeling, and insights into service quality across different airlines and travel classes.
Airline Sentiment Analysis & Passenger Insights

# Airline Sentiment Analysis & Passenger Insights

## 📌 Project Overview
This project analyzes **airline passenger reviews** to uncover patterns in overall ratings, sentiments, and service quality across different airlines.  
Using **data analysis, sentiment analysis, and topic modeling**, we aim to provide actionable insights for improving customer satisfaction in the airline industry.

---

## 🎯 Objectives
- Compare **Qantas Airways** ratings with the top 5 airlines over time.
- Identify **the airline with the most positive sentiment** overall.
- Determine **which airline has the highest positive sentiment** for Economy and Business Class services.
- Understand **passenger concerns and interests** when flying.
- Compare **topics from the top 3 airlines vs. bottom 3 airlines**.
- Provide **practical recommendations** to improve passenger experience.

---

## 📂 Dataset
- Passenger review dataset containing:
  - `AirlineName`, `CabinType`, `OverallScore`, `Review`
  - Service ratings: `FoodRating`, `SeatComfortRating`, `GroundServiceRating`, `EntertainmentRating`, etc.
  - Travel details: `DateFlown`, `OriginCountry`, `TravelType`
- Data cleaning & preprocessing performed in **Python**.

---

## 🛠️ Methodology
1. **Data Cleaning & Preprocessing**  
   - Remove missing values  
   - Standardize date formats  
   - Tokenize and preprocess text reviews  

2. **Sentiment Analysis**  
   - Used **VADER** to calculate sentiment polarity scores  
   - Ranked airlines by **average positive sentiment**  

3. **Trend Analysis**  
   - Compared **Qantas Airways** with top-rated airlines over time  

4. **Topic Modeling**  
   - Applied **LDA (Latent Dirichlet Allocation)** to extract topics  
   - Visualized results with **word clouds**  

5. **Insights & Recommendations**  
   - Identified improvement areas  
   - Suggested actionable strategies for better passenger support  

---

## 📊 Key Findings
### **1. Qantas Airways vs Top 5 Airlines**
- Qantas ratings remained **consistently lower** than competitors.
- Top 5 airlines maintained **higher and more stable ratings**.

### **2. Most Positive Sentiment Airline**
- **Hainan Airlines** received the highest average positive sentiment score.

### **3. Service Quality by Cabin**
- **Economy Class:** Hainan Airlines had the highest positive sentiment.  
- **Business Class:** Royal Air Maroc led with the highest positive sentiment.

### **4. Passenger Concerns & Interests**
- Common concerns: **refunds, delays, baggage issues, extra charges**.  
- Positive mentions: **friendly staff, comfort, in-flight meals**.

### **5. Top 3 vs Bottom 3 Airlines Topics**
- **Top 3 airlines:** focus on good service, food, comfort, and efficient staff.  
- **Bottom 3 airlines:** frequent mentions of delays, refunds, poor customer service.

---

## 💡 Practical Recommendations
- **Improve On-Time Performance**: Minimize delays and enhance communication during disruptions.
- **Enhance Baggage Handling**: Reduce lost or delayed baggage incidents.
- **Train Staff for Better Customer Service**: Focus on friendliness and responsiveness.
- **Upgrade In-flight Experience**: Invest in better meals, entertainment, and seat comfort.
- **Tailor Services by Cabin Class**: Maintain high standards in Economy and Business class services.
