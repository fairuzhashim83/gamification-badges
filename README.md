<!-- <!-- # gamification-badges -->
# 🏢 Designing Meaningful User Engagement Badges 
A mid-sized online community platform has rolled out a feature for users to post, reply to threads, give away items, recommend places, and organize local events. 
To increase retention and recognize positive participation, the product team is exploring a badge system that rewards consistent, meaningful activity. However, they want the badge logic to be **meaningful** and **balanced** (i.e not too easy/difficult to attain)


## 📌 Objectives
To provide data-driven insights and recommendations on the criteria to earn these badges. 

## 🏅 Proposed Badges and Criteria

| **Badge Name**              | **Description**                                                               | **Metric(s) Used**                           | **Threshold Template**                      |
| --------------------------- | ----------------------------------------------------------------------------- | -------------------------------------------- | ------------------------------------------- |
| **🎉 Event Planner**        | Recognizes users who organize well-attended community events                  | `events_created`, `event_participants` | ≥ **X** events with ≥ **Y** participants in **Z** weeks |
| **💬 Conversation Starter** | For users who spark discussions that receive replies                          | `posts_created`, `replies_received`    | ≥ **X** posts with ≥ **Y** replies in **Z** weeks       |
| **🎁 Philanthropist**       | Rewards those who regularly gift or share items via the marketplace           | `items_gifted`                            | ≥ **X** items gifted in **Z** weeks                 |
| **🤝 Helping Hand**         | For users frequently thanked by others — a sign of helpfulness and positivity | `thankyous_received`                      | ≥ **X** thank-you messages received in **Z** weeks  |
| **📍 Local Guide**          | Recognizes users who actively recommend local places and businesses           | `places_recommended`                      | ≥ **X** places recommended in **Z** weeks           |

## 📊 Dataset Summary
The dataset contains aggregated engagement metrics for users of a community platform, collected over the last 4, 6, 8, and 12 weeks. The dataset contains: 

| Column Name          | Description                                        |
| -------------------- | -------------------------------------------------- |
| `USER_ID`            | Unique user identifier                             |
| `LAST_X_WEEKS`       | Rolling timeframe for metric aggregation           |
| `POSTS_CREATED`      | Average posts created per week                     |
| `REPLIES_RECEIVED`   | Average replies received per week                  |
| `THANKYOUS_RECEIVED` | Average thank-you notes received per week          |
| `EVENTS_CREATED`     | Average events created per week                    |
| `EVENT_PARTICIPANTS` | Average participants per week across user's events |
| `ITEMS_GIFTED`       | Average items shared/gifted per week               |
| `PLACES_RECOMMENDED` | Average places recommended per week                |
