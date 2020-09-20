**Background:**

In Marketing Intelligence, analytics play a vital role in getting insights from data and using these to help optimize marketing campaigns. A very common use case that we find in marketing analytics is to predict hits and clicks for a website that helps the SEO or SEM analysts to better design their marketing strategies and optimize the important KPIs like Clicks Per Visit, Revenue Per Click, Cost Per Click etc.

**Objective:**

The focus of this analysis is to build a Machine Learning Model that can accurately predict number of hits per session.

**Data:**

A csv file containing information of about nine hundred thousand sessions. The columns should be understood as follows:
* row_num: a number uniquely identifying each row.
* locale: the platform of the session.
* day_of_week: Mon-Fri, the day of the week of the session.
* hour_of_day: 00-23, the hour of the day of the session.
* agent_id: the device used for the session.
* entry_page: describes the landing page of the session.
* path_id_set: shows all the locations that were visited during the session.
* traffic_type: indicates the channel the user cane through eg. search engine, email, ...
* session_duration: the duration in seconds of the session.
* hits: the number of interactions with the page during the session.

Predict for rows having missing values under "hits" column

**Evalution Metric:**

Root Mean Squared Error = sqrt(mean((actual - error)^2))
