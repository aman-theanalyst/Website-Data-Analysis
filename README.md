# Website-Data-Analysis

---

## 🛠️ Tools Used

- **Python**, **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib**
- **Google Colab**

---

## 🚀 Objectives

- Analyze how users arrive at the website (Channel Group breakdown).
- Understand engagement behavior (sessions, bounce, engagement time).
- Discover hourly traffic trends.
- Compare engaged vs non-engaged sessions by channel.
- Recommend data-driven strategies for improving engagement.

---

## 🧹 Data Cleaning

- Set the correct headers from the first row.
- Converted `Date-Hour` from string (e.g. `2024041723`) to datetime.
- Coerced numeric columns to proper data types.
- Derived `Hour` feature for temporal analysis.

---

## 📊 Analysis & Visualizations

### 📈 1. Traffic Trends Over Time
- Line chart showing **Sessions** and **Users** by timestamp.
- Identifies peak traffic windows.

### 📊 2. Top Channels by User Volume
- Bar chart grouped by `Channel Group`.
- Reveals which marketing channels drive the most users.

### ⏱️ 3. Average Engagement Time
- Engagement time visualized per channel.
- Helps identify channels that attract higher-quality traffic.

### 🔄 4. Engaged vs Non-Engaged Sessions
- Grouped bar chart showing split by channel.
- Highlights where traffic is bouncing or interacting.

### ⏰ 5. Hourly Heatmap
- Heatmap of sessions by `Hour` and `Channel Group`.
- Provides insights for optimal content/campaign scheduling.

---

## 🔍 Key Insights

- **Organic Search** and **Email** show higher engagement rates.
- Some channels (e.g., Display) drive traffic but with low engagement.
- Email traffic spikes in the morning; Social Media in the evening.
- Engagement rate should guide channel optimization, not just traffic volume.

---

## 💡 Recommendations

- Increase focus on **high-engagement channels**.
- Improve targeting and landing pages for low-engagement channels.
- Schedule campaigns based on peak **hourly traffic windows**.
- Prioritize **engagement rate** over raw traffic for success metrics.

---
