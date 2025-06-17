<!-- <!-- # gamification-badges -->
# 🏢 Designing Meaningful User Engagement Badges 
A mid-sized online community platform has rolled out a feature for users to post, reply to threads, give away items, recommend places, and organize local events. 
To increase retention and recognize positive participation, the product team is exploring a badge system that rewards consistent, meaningful activity (e.g. "Top Contributor", "Helpful Neighbor", "Event Organizer"). However, they want the badge logic to be **meaningful** and **balanced**

They’ve asked the data team to analyze 20,000 users’ engagement behavior — captured as weekly averages over the past 4, 6, 8, and 12 weeks — and recommend criteria for earning these badges. 


## 📌 Objectives

- Understand user behavior over different timeframes (4, 6, 8, 12 weeks)
- Identify stable and differentiating engagement metrics
- Recommend fair, data-driven badge thresholds

| **Badge Name**              | **Description**                                                               | **Metric(s) Used**                           | **Threshold Template**                      |
| --------------------------- | ----------------------------------------------------------------------------- | -------------------------------------------- | ------------------------------------------- |
| **🎉 Event Planner**        | Recognizes users who organize well-attended community events                  | `events_created`, `event_participants` | ≥ X events with ≥ Y participants in Z weeks |
| **💬 Conversation Starter** | For users who spark discussions that receive replies                          | `posts_created`, `replies_received`    | ≥ X posts with ≥ Y replies in Z weeks       |
| **🎁 Philanthropist**       | Rewards those who regularly gift or share items via the marketplace           | `items_gifted`                            | ≥ X items gifted in Z weeks                 |
| **🤝 Helping Hand**         | For users frequently thanked by others — a sign of helpfulness and positivity | `thankyous_received`                      | ≥ X thank-you messages received in Z weeks  |
| **📍 Local Guide**          | Recognizes users who actively recommend local places and businesses           | `places_recommended`                      | ≥ X places recommended in Z weeks           |
