# Portofolio_Analytics_Hearten
Repo contain couple of finished project regarding Data Analytics, Where recruiter can determine, some sort of level of capabilities for hiring the creator of the repository. 

# Data Description

The dataset includes the following fields:

- `final_ab_new_users_upd_us.csv` — contains information about all users who signed up in the online store from December 7 to 21, 2020. The fields in this file are:
- `final_ab_events_upd_us.csv` — contains information about all events that occurred for new users within the period from December 7, 2020 to January 1, 2021. The fields in this file are:
- `final_ab_participants_upd_us.csv` -contains information about the users who participated in the experiment. The fields in this file are:

1. Structure of `final_ab_new_users_upd_us.csv`:

- `user_id` - The unique identifier for the user
- `first_date` — The date the user signed up
- `region` - The region of the world where the user signed up
- `device` — The device the user used to sign up

2. Structure of `final_ab_events_upd_us.csv`:

- `user_id`
- `event_dt` — The date and time of the event
- `event_name` —The name of the event
- `details` — Additional data about the event, such as the order total in USD for purchase events

3. Structure of `final_ab_participants_upd_us.csv`:

- `user_id`
- `ab_test` — test name
- `group` — the test group the user belonged to
    
    
# Purposes

The international online store has asked us to complete an analytical task that their predecessor started but failed to complete. The predecessor launched an A/B test but then quit their job to start a watermelon farm in Brazil. They left only the technical specifications and the test results for the experiment, which is named recommender_system_test.

We will need to use the technical specifications and the test results to complete the analytical task. This will involve analyzing the data to determine which version of the recommender system performed better. We will then need to write a report that summarizes our findings and makes recommendations for how the online store can improve their recommender system.

- Then, we have to rerun the A/B test to testing changes of the number of events related to the introduction of an improved recommendation system.

# Libraries
*pandas, numpy, matplotlib, seaborn, plotly, scipy, math* 
