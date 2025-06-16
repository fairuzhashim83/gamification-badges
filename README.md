# gamification-badges

# 🔄 General Engagement Questions
 1. What is the overall distribution of user activity across the dataset?
 2. How many users are active (i.e., have non-zero values) in each time frame (4, 6, 8, 12 weeks)?
 3. How does engagement change with longer time frames — is it linear, exponential, or inconsistent?

# 📅 Time-Based Engagement
4. What are the mean, median, and percentile values (25th, 50th, 75th, 90th) for each metric in each time frame?
5. How many users would qualify for each badge under different potential thresholds (e.g., top 10%, top 25%)?
6. Are there clear natural cutoffs (e.g., elbow points) in the distribution of activity that can inform badge thresholds?

# 🏷️ Badge-Specific Questions
## 🧭 Event Planner
- What is the average number of events created per user in each time frame?
- How many participants do these events typically attract?
- Are there users who create many events but attract few participants (or vice versa)?
- What would a reasonable minimum for both Events_created and Event_participants be for someone to earn this badge?

## 💬 Conversation Starter
- What’s the average ratio of Replies_received to Posts_created per user?
- Do users with many posts tend to receive more replies, or is there no clear pattern?
- What threshold of replies per post would indicate successful conversations?

## 🎁 Philanthropist
- How common is it for users to gift items — what percentage of users gifted at least once?
- What is the distribution of Items_gifted per user?
- Are there extreme outliers, and should they influence badge criteria?

## 🙌 Helping Hand
- How many users received thankyou messages?
- Is receiving thankyous strongly correlated with other behaviors (e.g., posting or gifting)?
- What number of thankyous separates top contributors from the average user?

## 📍 Local Guide
- How many users recommend places, and how frequently?
- Are place recommendations clustered among a few users or evenly distributed?
- Should the badge encourage more users to recommend places or reward the most prolific recommenders?

# 📊 Comparative & Strategic Questions
- Which engagement metrics are most correlated with one another?
- Are there clusters of users who are highly active in multiple areas (e.g., social and event-related)?
- Would setting the same time period (Z) for all badges be fair, or should it vary based on behavior frequency?