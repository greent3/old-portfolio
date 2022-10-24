{
    "title":"E. Investigating User Decline",
    "link":"https://github.com/greent3/Investigating_User_Decline/blob/main/Yammer%20Investigation.ipynb",
    "image":"/img/whats_this.png",
    "description":"SITUATION: You show up to work one morning and the head of the product team asks you what you think about the latest activity on the user engagement dashboards. You fire them up, and notice a decline in users over the past 2 months. \n ACTION: Using focused SQL queries to gather data about user events over the past month and Excel for data visualization, I was able to attribute the decline in users to the following: ...",
    "tags":["SQL", "Excel", "Data Analysis", "Jupyter"],
    "featured":true
}


#### SITUATION:
You show up to work one morning and the head of the product team asks you what you think about the latest activity on the user engagement dashboards. You fire them up, and notice a decline in users over the past 2 months.

#### ACTION:
Using focused SQL queries to gather data about user events over the past couple months and Excel for data visualization, I was able to provide the following conclusions and recommendations.

#### CONCLUSIONS:
1) Considering we hit a new ATH for new users created on the week of 28July, and that most of our events come from established user engagement, It’s unlikely that the sharp decline is correlated with a drop in new user sign-ups.

2) The decline in weekly active users beginning on 28July could be due to multiple factors:

      a) On the week of 28July, our 2nd largest user, Company with ID# 2, saw an overall decrease in events of 42% from the week prior. This decrease percentage was roughly the same across the Company 2’s top 10 contributing countries, and is therefore unlikely related to a geographical event like a localized holiday or natural disaster.

      b) Beginning 28 July, when measuring Company2’s general events, or events that aren’t related to signing up, the decrease in events related to Yammer’s search functionality was 22% higher than the decrease in events not related to yammers search functionality.

      c) This observation is even stronger the following week, with the average decrease in search functionality related events being 48% more than the ones unrelated. This could mean that the search results being provided to company2 are not useful, or irrelevant.

3) Lastly, on average, our click-through-rate for our weekly emails that get opened have been decreasing across all companies since 21 July. This might mean our emails are becoming less and less interesting or relevant to users.

#### RECOMMENDATIONS:
1) I recommend we reach out to users at company2 to get feedback on our apps search functionality and see if they’ve started using a competitor's product.

2) If we’ve recently changed some code in our search functionality or information in user profiles for company2, it might be worth changing them back until we figure out why the new changes are unpopular among company2's users.

3) Lastly, along with taking a close look at 28July’s unpopular weekly digest email, we could implement some A/B testing for our weekly digest emails to improve our % of opened emails and average click through rate.
