# Portofolio_Analytics_Hearten
Repo contain couple of finished project regarding Data Analytics, Where recruiter can determine, some sort of level of capabilities for hiring the creator of the repository. 

# Data Description

With Five Data Set 

1. `/datasets/megaline_calls.csv`
2. `/datasets/megaline_internet.csv`
3. `/datasets/megaline_messages.csv`
4. `/datasets/megaline_plans.csv`
5. `/datasets/megaline_users.csv`

Telecommunication company that provide 500 user to be anlyze 

Dataset `calls`(call data):

- `id` - ID for Unique web session
- `call_date` - Date when a call is on going
- `duration` - The amount of time call been 
- `user_id` - Car Value in Dollar

Dataset `Internet` (web session data):

- `id` — Unique web session ID
- `call_date` — the volume of data consumed during the session (in megabytes)
- `duration` — web session date
- `user_id` — User ID

Table `messages` (data SMS):

- `id` — A unique SMS ID
- `message_date` — the date the SMS was sent
- `user_id` — ID of the user who sent the SMS

Table `users` (data user):

- `user_id` — User ID
- `first_name` — the user's first name
- `last_name` — user's last name
- `age` — user's age (years)
- `reg_date` — subscription start date (dd, mm, yy)
- `churn_date` — the date the user stopped using the service (if the value is missing or not present, the service plan was in use when this data was generated)
- `city` — the city where the user lives
- `plan` — the name of the phone plan

Table `plans` (phone plan data):

- `plan_name` — the phone's package name
- `usd_monthly_fee` — monthly fee in US dollars
- `minutes_included` — monthly allocation of calling minutes
- `messages_included` — monthly SMS allocation
- `mb_per_month_included` — monthly data volume allocation (in megabytes)
- `usd_per_minute` — price per minute if the package allocation limit has been exceeded (for example, if a package has an allocation of 100 minutes, then usage starting from the 101st minute will be charged)
- `usd_per_message` — price per SMS if the package allocation limit has been exceeded
- `usd_per_gb` — price per extra gigabyte of data if the package allocation limit has - `been exceeded` (1 GB = 1024 megabytes)


# Purposes

After conducting an analysis of the data provided, there is a significant difference between the two quota packages, namely the $20 surf package and the $70 ultimate package. A difference of $50 is observed from the quota packages provided by Magline which has its own advantages for each package. However, more revenue is obtained from the surf quota package. This is because users tend to use quotas that exceed the quota package provided by Magline.
