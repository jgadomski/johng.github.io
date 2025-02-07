---
name: Final Project Part 3.1
tools: [Python, HTML, vega-lite]
image: IS445/assets/chart1.png
description: by John Gadomski
custom_js:
  - vega.min
  - vega-lite.min
  - plotly
  - matplotlib.pyplot
---

# Unleashing the Power of NFL Big Data: An Interactive Exploration
#### The National Football League (NFL) is one of the most popular sports leagues in the world, with millions of fans tuning in each week to watch their favorite teams and players. But what goes on behind the scenes? How do coaches and players use data to gain an edge on the competition? In this article, we will take a deep dive into the world of NFL data and explore some of the most fascinating trends from the past few seasons.

By John Gadomski 

Final Project Part 3.1

Our primary dataset is the NFL Big Data set, which contains both information on player and team performance, as well as weather statistics including location and wind speed. Using this dataset, we will create an interactive visualization that allows users to explore player performance across different variables. 

Main Interactive Visualization: 

Analyzing player height and weight in the NFL can provide us with valuable insights into the sport. By using position as a tooltip variable, we can observe how different positions require different physical attributes. For example, players like cornerbacks and wide receivers tend to be smaller in stature and have lower body weights. On the other hand, positions like offensive and defensive linemen require larger body sizes and higher body weights.

This information can be useful for coaches and team managers when selecting and training players for specific positions. It can also help in identifying potential talent based on physical attributes. Additionally, analyzing player height and weight can provide insights into trends and changes in the sport over time, such as changes in playing styles and positions. Overall, analyzing player height and weight can provide valuable information for improving player performance and enhancing team strategy.

![figure 01](/assets/assets/newplot.png)
Figure 1: <br />
Creator: John Gadomski  <br />
Description: Interactive Plot that allows you to choose specific player and see their height, weight, and position

As a user, I can hover over the data points on the scatter plot and see the player name in the tooltip that pops up. By using the tooltip feature to check for player name, I can quickly identify specific players on the plot and see where they fall in terms of their height, weight, and position. This could be particularly useful for coaches and analysts who are looking to evaluate players' physical attributes in order to determine their role on the team or their potential for success at the professional level.

Analyzing the tendencies of players' height and weight by position can provide valuable insights for NFL analysts and coaches. For example, knowing that cornerbacks and wide receivers tend to be smaller and lighter than other positions, such as linemen or linebackers, can help coaches make more informed decisions when drafting or signing players. By analyzing the height and weight of successful players at a particular position, coaches and analysts can also identify physical attributes that may be indicative of success in that position. This type of analysis could help teams identify hidden gems in the draft or free agency, or help them make more informed decisions when building their roster. Ultimately, understanding the tendencies of players' height and weight by position can help teams gain a competitive advantage in a league where even small differences can make a big impact.

![figure 02](/assets/assets/chooseplayer.png)
Figure 2: <br />
Creator: John Gadomski  <br />
Description: Interactive Plot that allows you to choose specific player and see their height, weight, and position


![figure 03](/IS445/assets/chart1.png)
Figure 3: 
Creator: John Gadomski  <br />
Description: Analyzing the count of NFL players by position can give insights into team management decision-making processes. Teams need to allocate their budget carefully in free agency and the draft to address team needs and maintain a balanced roster. By examining the distribution of players by position, teams can make informed decisions about where to focus their resources. For example, if there are an insufficient number of defensive linemen on a team, the team management may decide to allocate resources towards acquiring or developing more defensive linemen. Thus, analyzing player counts by position can help teams make informed decisions about how to build their rosters and allocate their budget effectively.

![figure 04](/IS445/assets/chart2.png)
Figure 4: 
Creator: John Gadomski  <br />
Description: The temperature vs humidity visualization can provide valuable insights into how weather conditions can impact NFL games. High humidity levels combined with high temperatures can lead to an uncomfortable playing environment for athletes, potentially affecting their performance. Similarly, cold and dry conditions can also impact players, affecting their grip on the ball and potentially leading to more fumbles. Understanding the relationship between temperature and humidity can help coaches and analysts better prepare for games, such as adjusting their strategies based on weather conditions or adjusting player training and hydration programs. Additionally, this visualization can be useful for predicting game outcomes based on weather conditions, allowing analysts to make more informed decisions when placing bets or making predictions

![figure 05](/IS445/assets/chart3.png)
Figure 5: 
Creator: John Gadomski  <br />
Description: Analyzing the relationship between height and weight in NFL players can provide insights into the physical demands of each position on the field. For instance, cornerbacks and wide receivers tend to be smaller and lighter, while offensive linemen and defensive tackles are generally larger and heavier. This information can be useful for coaches and analysts who want to create game strategies and design training programs that cater to the specific physical demands of each position. By looking at the scatter plot of height and weight, and using the tooltip feature to see the position of each player, coaches and analysts can identify patterns in the physical characteristics of players in different positions, and make more informed decisions about how to train and prepare for games. Overall, analyzing the relationship between height and weight in NFL players can provide valuable insights into the physical demands of each position and can help coaches and analysts create more effective training programs and game strategies.

In conclusion, the use of analytics has become an integral part of the player drafting process in the NFL. Teams can use data-driven insights to evaluate the potential of draft prospects and make informed decisions on who to select. With the vast amounts of data available, including player statistics, biometric data, and even social media analytics, teams can gain a more comprehensive understanding of a player's potential on and off the field. By leveraging the power of analytics, teams can build a more successful and competitive roster, ultimately leading to greater success on the field.

{% include elements/button.html link="https://github.com/jgadomski/jgadomski.github.io/blob/main/_data/NFLPlayer.csv" text="The Player Data" %}
{% include elements/button.html link="https://github.com/jgadomski/jgadomski.github.io/blob/main/_data/Weather.csv" text="The Weather Data" %}
{% include elements/button.html link="https://github.com/jgadomski/jgadomski.github.io/blob/main/python_notebooks/%5BIS445%5DFinalProjectPart3Code.ipynb" text="The Analysis" %}

Source of data: https://www.kaggle.com/competitions/nfl-big-data-bowl-2020 
