# ComCast-Analysis.

# Comcast Telecom Consumer Complaints Analysis

## Business Case

**Comcast** is a global telecommunication company based in America. Despite being a significant player in the market, they have faced consistent challenges related to customer service. The company has received a large number of consumer complaints, leading to a fine of $2.3 million in October 2016.

This project aims to analyze a dataset containing customer complaints to:
- Identify trends in the complaints.
- Understand the domains where most complaints are coming from.
- Determine the states with the highest number of complaints and unresolved complaints.
- Assess the efficiency of their customer service channels (Internet and Customer Care Calls) in resolving complaints.

## Dataset

The dataset contains the following columns:
- `Ticket #`: Ticket number assigned to each complaint.
- `Customer Complaint`: Description of the complaint.
- `Date`: Date of the complaint.
- `Time`: Time of the complaint.
- `Received Via`: Mode of communication of the complaint.
- `City`: Customer's city.
- `State`: Customer's state.
- `Zip code`: Customer's zip code.
- `Status`: Status of the complaint (Open, Closed, Solved, Pending).
- `Filing on Behalf of Someone`: Indicates if the complaint was filed on behalf of someone else.

## Analysis

### 1. **Trend Analysis**:
- Plotted a trend chart for the number of complaints at both monthly and daily granularity levels.

### 2. **Complaint Types**:
- Identified and tabulated the frequency of complaint types.
- Found that issues related to "Internet" and "Data Cap" are among the top concerns of customers.

### 3. **Status Categorization**:
- Categorized the status of complaints into two categories: "Open" (includes 'Open' & 'Pending') and "Closed" (includes 'Closed' & 'Solved').

### 4. **State-wise Analysis**:
- Visualized the state-wise distribution of complaints using a stacked bar chart.
- Identified that Georgia has the maximum complaints, while Kansas has the highest percentage of unresolved complaints.

### 5. **Efficiency of Customer Service Channels**:
- Calculated that approximately 76.75% of complaints received through the Internet or customer care calls have been resolved to date.

## Insights
- There's a significant spike in complaints in June.
- "Internet" and "Data Cap" related issues are prevalent among customers.
- While Georgia has the highest number of complaints, Kansas needs attention as a significant portion of its complaints remains unresolved.

## Conclusion

Through this analysis, Comcast can gain actionable insights into improving its customer service, focusing on specific states, and addressing prevalent issues faced by its consumers.

## Tools & Libraries Used
- **Python**
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
