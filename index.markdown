---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

_Yue Zhou_  - s232893

_Jia Wei_  - s233486

Group 15

Our website : https://github.com/To1and/to1and.github.io/blob/main/notebook/Final%20Project.ipynb

## Motivation

### What is your dataset?
Our main dataset is called MovieLens Dataset (consists of movies released on or before July 2017). It's 33 MB, including 45572 rows (That is to say, it includes data for a total of 45,572 movies), 24 variables. We also introduce several other related dataset like rating, keywords and credits for reference. The total size of all data is approximately 900 MB.


### Why did you choose this/these particular dataset(s)?
Analyzing this dataset is a strategic choice for understanding the intricate relationship between movie elements and financial performance. It offers a comprehensive view of various factors that influence a movie's financial outcomes, such as genres, budgets, revenues, and ratings.

Firstly, the dataset contains a wealth of information, including genres, budgets, and revenue figures, providing insights into the economic dynamics of the film industry. By examining these elements, we can uncover patterns like which genres are more profitable, the relationship between production budgets and box office success, and how ratings influence audience preferences.

Moreover, the inclusion of production companies, countries, and release dates enables us to analyze trends over time and understand the evolving landscape of the movie industry. This temporal analysis helps identify shifts like the impact of streaming platforms and changing audience tastes, offering valuable insights for forecasting future trends.

In summary, this dataset provides a rich foundation for data-driven decision-making. By exploring the relationships between different movie elements and financial performance, stakeholders can make informed choices on budgeting, genre focus, and marketing strategies to navigate the ever-changing film industry landscape effectively.

## Data Analysis & Visualizations

### A glance at title and overview

Do certain words appear more frequently in movie titles and descriptions? It seems likely that some words are deemed more impactful and suitable for a title. Let's investigate this further!
    
![png](assets\images\output_15_0.png)
    
The word cloud visualizes the most frequently used words in movie titles, with the size of each word reflecting its frequency. The word **Man** and **Day** tops the list of most frequently used words in movie titles, followed by **Night**, **Love**, and **Movie**. This trend underscores the pervasive theme of daily life in movies.
    
![png](assets\images\output_17_0.png)

We can see **Life** and **Find** are popular in Movie Blurbs. Together with **World**, **Family** and **Love**, these wordclouds give us a pretty good idea of the most popular themes present in movies which center on personal journeys, relationships, and human experiences, with a strong emphasis on discovery, daily life, and emotional connections. 

### What kind of title could be more profitable?

Above is just a summary of the overall data. Now we're moving on to a more interesting part. To intuitively reflect the possible relationship between movie financial performance and titles, we will weight each word in the movie title by its cost and create a new chart like this.
    
![png](assets\images\output_21_0.png)

    
![png](assets\images\output_22_1.png)

![png](assets\images\output_23_1.png)
    

Surprisingly, possibly contrary to the real world, **man** and **men** spent more money if they appear in a movie title, suggesting that high-budget films often focus on key male character and individual heroism. 

And accordingly **star** also makes a lot of money along with the word **man**, revealing audience preferences for films. I think this makes sense, given that Star Wars is an extremely successful series with many installments. 

As for the return rate, aside from **man** and **star**, it's hard not to notice the words **Harry** and **Potter**, as very few other movies would include these two words. This further confirms the immense commercial success of Harry Potter, which could be one of the most successful movie series in history. Is that the case? Please be patient, we'll reveal more to you later.

Then we are about to talk about the overview of movie. What kind of plot or theme is more appealing? What kind of theme might lead to a movie's failure? Let's explore that now.
    
![png](assets\images\output_26_1.png)
 
    
![png](assets\images\output_27_1.png)

    
![png](assets\images\output_28_1.png)
    


In terms of the overview, we can clearly see the words **world** and **man**, which might indicate that most high-budget movies are filmed with a grand theme or focus on a specific character. 

The same applies to movies with high box office revenue, but from the other two words **new** and **life**, we can also recognize that audiences are more looking forward to new things and life-related themes.

The return on investment also shows us that grand perspective, novelty, and life story are likely essential elements in making a movie more successful according to the same three words.

### Which country makes most profitable Movies?

Unsurprisingly, the majority of movies in our existing data are produced in the United States and speaking english, nearly 80% of our total data. But are American movies definitely the most profitable? Which country's movies have the highest cost-effectiveness and returns? We will explore this next.

    
![png](assets\images\output_35_0.png)
    

![png](assets\images\output_36_0.png)
    


We can see that even though the United States produces the most films, their average production cost is still not the highest. 

Australia, with a much smaller output of films, stands out with the highest average production cost at $9.5 million per film, while its average revenue reaches $20.5 million per film. This indicates that Australian films, though fewer in number, are often high-investment projects that yield substantial returns. The United Kingdom follows with a budget of $6.4 million and revenue of $17.9 million, a profit of about $11.4 million per film.

Other countries like Canada ($5.2 million budget, $10.4 million revenue) and France ($3.1 million budget, $5.1 million revenue) show smaller profits of $52.2 million and $19.9 million per film, respectively. Countries with lower budgets, like India ($2.8 million budget, $3.9 million revenue), have even smaller profits of about $1.1 million per film.

In contrast, the United States has the highest average revenue per film worldwide, with an average revenue of $22.52 million per film and an average production cost of about $8.14 million. This might be a little-known fact because Australia's film industry isn't very well-known.

### What is the most successful Franchise?

    
![png](assets\images\output_40_0.png)
    

Among the top 10 movie collections by revenue, the **Harry Potter Collection** stands out as the highest-grossing franchise, amassing an impressive total revenue of $7.71 billion across 8 movies, averaging $963.4 million per film. On the other end of the spectrum, the **Jurassic Park Collection** ranks as the lowest-grossing among the top 10, generating $3.03 billion from 4 movies, with an average revenue of $757.9 million per film.

Notably, the **James Bond Collection** is the most prolific, with 26 movies contributing to a significant total revenue of $7.11 billion. Despite this vast output, the collection's average revenue per movie sits at a comparatively modest $273.3 million.


Among these film franchises, when comparing the average revenue per film, The **Avengers Collection** tops the list with a staggering average of $1.4625 billion per film, showcasing its extraordinary global appeal. In contrast, the **Transformers Collection** series ranks at the bottom with an average revenue of $873.22 million per film, still a respectable performance despite being at the lower end. 

Other notable franchises include **Avatar Collection** and **Finding Nemo Collection**, both maintaining strong average revenues. It's worth noting that despite both containing eight films, the **Harry Potter Collection** and **Star Wars Collection** franchises still boast average revenues of over $900 million, further cementing their enduring appeal among audiences.

    
![png](assets\images\output_45_0.png)


The chart of the top 10 movie collections by total and average budget reveals that the **James Bond Collection** has the highest cumulative budget at $1.54 billion across 26 films, though its average budget per film is the lowest at $59.2 million, reflecting a cost-efficient approach over its extensive run. In contrast, the **Mission: Impossible Collection** is the most conservative in total spending, with a budget of $650 million across 5 films, averaging $130 million per film.

When focusing on average budget per film,  the **Pirates of the Caribbean Collection** claims the title of the most lavish, with an average budget of $250 million per movie across 5 films, culminating in a total budget of $1.25 billion. Meanwhile, the **Harry Potter Collection**, with a total budget of $1.32 billion across 8 films, averages $165 million per film, balancing significant investment with a consistent output.



### What's the most profitable genre?

When it comes to movie genres, everyone has different preferences. But we wanted to do some analysis to find a relationship between the genre of movies and their commercial success.

Let’s first take a look at the proportion distribution of all movie genre in our data set.

![png](assets\images\output_52_0.png)
    
The pie chart illustrating the proportion of total movies by genre shows Drama as the most dominant category, comprising 24.6% of all films, followed by Comedy at 19.9% and Action at 18.0%. Adventure and Horror each account for 7.8% and 5.9% respectively, while genres like Crime (5.0%), Thriller (3.7%), Animation (2.7%), Fantasy (2.6%), and Romance (2.3%) represent smaller shares. The "Other" category, capturing miscellaneous genres, makes up 7.6%, indicating that while Drama, Comedy, and Action dominate production, a diverse range of genres still contributes to the overall cinematic landscape.

![png](assets\images\output_53_0.png)
    
The refined bubble chart of movie genres plots budget versus revenue. Family, Animation, and Adventure genres cluster in the upper-right quadrant, with average budgets around 550-700 million and revenues exceeding 200 million, indicating both high investment and strong returns.Meanwhile, it's interesting that TV movie has similar revenue with Horror, Drama, Music, Western, but the budget is significantly lower, by three or four times.

![png](assets\images\output_54_0.png)

![png](assets\images\output_54_1.png)

The most supported movies by audiences are Family and Animation movie, approaching 250 million, followed closely by Adventure, around 200 million. While Documentary and Foreign movies are at the bottom of both average revenue and budget.

Animation leading with the highest average budget, exceeding 650 million, followed by Adventure and Family at approximately 600 million each.

Genres like Family, Animation, and Adventure, backed by hefty budgets, dominate revenue charts, reflecting audience demand for immersive, family-friendly spectacles. Science Fiction and Fantasy also thrive, balancing moderate budgets with strong returns. However, making war movies is a challenge because they come with high production costs, yet their returns are relatively modest.


### Do votes matter?

Although we may already know that a commercially successful film will not necessarily receive higher ratings from audiences, and vice versa. But we still want to thoroughly explore how much connection a movie's score has with its commercial success?

![png](assets\images\output_58_0.png)
    

![png](assets\images\output_59_0.png)

    
![png](assets\images\output_60_0.png)
    


In all of the above graphs, we can generally find that costs and benefits do not show a positive or negative correlation with ratings, and that the vast majority of films fall within a range of about four to eight. In the graph about returns we can again recognise that the vast majority of more commercially successful films do not receive a lower rating, but very high ratings do not imply extremely high returns either. This could mean that the most commercially acceptable films are more likely to have a higher return on investment, in short, a film that makes money is not necessarily of high artistic merit.

At this point, we can try to filter out the film entries with less than 1000 votes and graph them again to see how the relatively more famous films perform


![png](assets\images\output_62_0.png)
    

![png](assets\images\output_63_0.png)


    
![png](assets\images\output_64_0.png)
    


Here, we can see that even among relatively famous films, costs and benefits do not have any direct correlation with ratings, which is a very intuitive conclusion for us.



According to our observations, suppose we take films with ratings greater than 7.5 as so-called great films and analyse them, what would happen?


    
![png](assets\images\output_67_0.png)
   
![png](assets\images\output_68_0.png)
    

    
![png](assets\images\output_69_0.png)
    


The graphs reveal that while high-rated movies generally have budgets and revenues clustered in lower ranges, a select few with ratings above 8.0 don't show significantly higher budgets and revenues. Overall, it's obviously not true that movies with higher ratings tend to have proportionally higher budgets and revenues, which suggests that we can't simply make a direct link between a film's financial figures and its artistic success or failure.The vast majority of high-scoring films will have returns concentrated within the 0 to 5 range.

### Are films more profitable now than they once were?

Let me start by looking at the trends in film revenues and costs over time


![png](assets\images\output_73_0.png)
    

    
![png](assets\images\output_74_0.png)
    


It is quite common sense to see that the costs and revenues of the film industry are gradually increasing as time changes. 

Once upon a time, in the early days of cinema around the 1920s, making movies was a small business. The graph for "Average Budget Over Time" shows that budgets were super low, mostly staying below $0.5 million USD. There was a tiny spike in the 1920s, maybe because of a big silent film, but then it stayed quiet for a long time. This tells us that back then, films didn’t need huge money to get made.

Fast forward to the 1960s and 1970s, and things started to change a little. Budgets began to creep up, with some movies costing around $1 million or more. But the real jump happened after the 1990s! The graph shows a massive rise, with budgets shooting up to over $3.5 million by 2020. This means filmmakers were spending a lot more to create movies, probably because of fancy special effects and big stars.

Now, let’s look at the "Average Revenue Over Time" graph. In the early years, revenue was almost nothing, just like the budgets. But starting in the 1980s, it started to grow, and by the 2000s, it exploded! Revenues reached over $2 million USD, showing that movies were making a lot more money than before.

Even though budgets have gone way up, revenues have grown even faster, especially since the 2000s. This suggests that modern movies, with their big budgets, are bringing in bigger profits compared to the old days when both costs and earnings were low.

But what about the profitability of films?

    
![png](assets\images\output_76_0.png)
 

Back in the 1920s, the return rate for movies was wild—sometimes jumping as high as 40%! This means that for every dollar spent, some movies made a lot more money back then. But it wasn’t steady; the graph shows big ups and downs, with many films barely making any profit.

As we move to the 1940s and 1950s, the return rate stayed shaky, with some movies hitting 20% or 30%, but most were much lower. It was like a rollercoaster—some films did great, while others didn’t make much. Then, around the 1970s, things started to get more crowded. The graph gets super dense, showing lots of movies being made, but the return rates were still all over the place, mostly staying below 20%.

By the 2000s and 2010s, the return rates are still jumping between 0% and 50%, but most movies seem to cluster closer to the lower end, around 10% to 20%. This tells us that while some films still made huge profits, most movies weren’t as profitable as the lucky ones from the early days.

So, are films more profitable now? Not really. Even though the earlier graphs showed that revenues are much higher today, this return rate graph shows that profits compared to budgets haven’t grown much. In the past, a small budget could lead to a massive return, like 40%. Now, even with bigger budgets and revenues, the return rate is often lower, meaning the profit margin isn’t as good. Movies today might make more money, but they’re not always more profitable!

<iframe src='assets\images\budget_revenue_timeline' width='700px' height='600px'></iframe>

The "Interactive Cumulative Timeline (Budget vs Revenue)" graph shows how films have evolved from 1915 to 2017. Picture the early days around 1915—budgets were tiny, often under $100,000, and revenues were just as small, barely hitting a million dollars. The graph starts with a few scattered dots, showing that only a handful of movies made any money back then.

As we slide the timeline to the 1950s and 1960s, more dots appear, and budgets start creeping up to around $1 million or $2 million. Revenues grow too, sometimes reaching $10 million for the lucky films. It’s like the movie industry was waking up, with more people making and watching films. By the 1970s and 1980s, the graph gets busier—budgets hit $5 million to $10 million, and revenues climb higher, with some movies earning over $100 million. The dots start clustering, showing a growing number of big-budget films.

Fast forward to the 2000s and 2010s, and the graph explodes with color! Budgets soar to $350 million, painted in bright yellow and orange, while revenues reach billions, with dots stretching up to $10 billion. The colors show how budgets have gotten huge—dark purple for $50 million, red for $200 million, and yellow for $350 million. It’s like a fireworks show of money, with blockbuster movies dominating the scene.