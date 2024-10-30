# Phase 2 Project Description
Group Members:
Github: [Github](https://github.com/Luwate/dsc-phase-2-project-v3)
Tableau Dashboard: [Tableau](https://public.tableau.com/app/profile/boniface.mutwiri/viz/Phase2projecttableaudashboard/Dashboard2)


# Overview
Like many other industries, the movie industry was feared to fail in the midst of the global pandemic that gripped the world in 2020. While 2020 and 2021 proved to be especially tricky years for the industry, it has since recovered to pre-2020 levels and is expected to continue to grow strongly throughout the rest of the decade. Therefore, it would be prudent to investigate the viability of creating a new studio, which would not only contribute to the increased market capitalisation of the industry but more importantly, would allow more original stories to be told.

G2 corp. has been successful in the various ventures that it has had a stake in, however this does not guarantee success in its future ventures. Thus it is vital to conduct analysis to help determine what type of movies, targeted at which markets and produced by which director in order to maximise the chance of success.

# Business Understanding
## Problem Statement
G2 corp. has expressed interest in creating a movie studio, however the organisation lacks expertise in this field. This project aims to assist the organisation in determining a variety of factors, primarily: What genre of movies should be produced, What markets should be targeted, Which directors should be contracted, How much budget should be allocated to the movies based on the genre.

## Expected Benefits
Through the analysis of the available data, the organisation will have the ability to make an data-informed decision about the kind of movies to produce in order to maximise the chances of success

## Business Success Criteria
Success of the project will be evaluated through the execution of the recommendations made after the analysis has been completed.

## Assessment
The data available is fragmented into 4 different data sources from Box Office Mojo, IMDB, TheMovieDB and The Numbers. This data contains information about the movie itself, financial data as well as how the movie was received.

The risk of this project comes down to the nature of movies. Movies are a piece of art and like any other artform, it is difficult to engineer the success of a movie. The right combination of genre, budget and director may still produce a film that is unsuccessful financially. Therefore while this analysis will be important and necessary, it cannot be treated as the single key to success.

## Project Goals
- Combine and clean the datasets
- Analyse the data based on the criteria that contribute to a movie’s success
- Identify genres, regions, budgets and (WRITERS) that will likely produce artistically and financially successful movies
- Provide final recommendations to stakeholders

## Project Success Criteria 
The project will be considered a success upon the recommendation of a combination of region, director, budget and (WRITERS) for specific genres which G2 Corp. should pursue.

## Data Understanding
The data cleaning process undertaken involved several crucial steps to enhance the quality and usability of the dataset. Initially, a thorough assessment of the dataset was conducted, focusing on missing values and data types. This allowed us to identify columns with significant missing data, particularly in `original_language`, `region`, and `runtime_minutes`, which required immediate attention.

## Data Preparation
To address missing values, different strategies were adopted tailored to the nature of each column. For the `death_year` column, we filled missing entries with `-1`, signaling an unknown death year, which provides a clear method for future filtering and analysis. For categorical columns such as `original_language` and `region`, missing values were replaced with the placeholder "Unknown" to maintain uniformity and ensure that these columns could still be effectively analyzed. In the case of the numerical column `runtime_minutes`, missing values were filled with with the mean, preserving the dataset's overall distribution while allowing for continued analysis.

## Analysis
The analysis focused on various key visualizations within the film industry, including genre-based ratings, the relationship between production budgets and foreign box office performance, and the impact of movie writers on film success. The following are the major insights drawn from the visualizations:

1. Top 10 and Least 10 Genres by Average Rating
The first set of graphs, labeled as Top and Least 10 Genres by Average Rating, demonstrates notable disparities in how different genres are received by audiences.

High-Performing Genres: Genres such as Action Drama, Documentary History, and Adventure Drama Fantasy received some of the highest average ratings, often scoring between 7.5 and 8 out of 10. These findings suggest that films with engaging narratives, historical content, or adventure elements tend to resonate positively with both audiences and critics.
Underperforming Genres: In contrast, the least-rated genres, including Comedy Romance, Horror, and Action Fantasy, exhibited much lower ratings, averaging around 5 to 6. These genres may struggle with audience expectations, possibly due to formulaic storytelling or a lack of depth, indicating a need for more innovative narratives within these categories.
This analysis suggests that genre selection plays a critical role in a film’s success. Filmmakers aiming for critical acclaim might benefit from choosing genres with higher historical success, while those operating in underperforming categories may need to invest in creative innovation.

2. Relationship Between Production Budget and Foreign Gross Revenue
The second set of graphs illustrates the relationship between production budgets and foreign box office performance for films.

High Budget Correlation: In general, the graphs indicate a trend where higher-budget films earn higher gross revenues internationally. Steven Zaillian's films, for example, had the highest production budgets among the top-rated writers, suggesting that investment in larger projects often results in higher financial returns.
Low-Budget Success Stories: However, exceptions were observed where films with modest budgets managed to achieve significant box office success. This suggests that factors like effective storytelling, marketing strategies, and audience engagement can sometimes outweigh the effect of budget alone. This insight is valuable for independent filmmakers who may have to work with constrained budgets but can still capture market attention through creative strategies.
3. Top and Least Rated Writers
The final graphs offer insights into the performance of film writers by analyzing their average movie ratings.

Top Writers: Writers such as Anthony McCarten, Steven Zaillian, and Edgar Wright consistently produced films with high average ratings, reflecting their ability to create stories that connect well with audiences and critics. Their work often involves a blend of strong narrative elements and innovative storytelling, which contributes to their consistent success.
Underperforming Writers: On the other hand, the least-rated writers, including James Gunn and Justin Theroux, showed lower average ratings. Many of these writers are associated with films that were part of poorly received franchises, suggesting that the quality of collaborations and project choices may significantly impact ratings. Interestingly, several writers in this group are relatively early in their careers, indicating potential for growth with the right projects and guidance.

4. Graph of Top 10 Rated Writers Average Grossing Figures and Production Budgets (Budget < $55M):

Showed how certain writers performed with films under $55 million budgets.
Displayed both worldwide gross (green bars) and production budgets (red bars) for top-rated writers like Edgar Wright, Ethan Coen, Joel Coen, and Anthony McCarten.

5. Graph of Top 10 Writers with Highest Worldwide Grossing Figures and Production Budgets:

Highlighted writers such as Christopher Nolan, Jonathan Nolan, and Jim Starlin with significantly high grossing films (over $750 million) but with production budgets typically above $100 million.

6. Top and Least Rated Genres with Average Ratings:

Analyzed genres by their average ratings under budget constraints of $50 million.
Showed that genres like Action-Drama and Documentary-History scored highly, while genres like Comedy-Romance and Horror had lower ratings.

7. Additional Comparison of Writers by Average Movie Ratings:

Compared the performance of top and least-rated writers. Top-rated writers produced films with high average ratings (~7-8), while least-rated writers hovered around 4-5.

### Recommendations
#### Focus on English-Language Films with International Appeal:
G2 Corp. should concentrate on producing movies in English and exporting these movies internationally, as the data indicates that films with English as the original language tend to perform better in terms of gross revenue. Targeting global audiences with English-language content offers a higher likelihood of commercial success.

#### Leverage Drama in Combination with Popular Genres and High-Grossing Writers:
The best-received genre is drama, often combined with other genres such as action, adventure, sci-fi, or thrillers. For the highest-grossing films, G2 Corp. may consider collaborating with writers such as Christopher Nolan, Jonathan Nolan, Lee Unkrich, Michael Arndt, and Anthony McCarten, or a group of comic book writers like Jim Starlin, Bill Mantlo, Keith Giffen, and Steve Englehart.

Films created by these writers typically generate more than $750 million in revenue, but they also tend to involve production budgets exceeding $100 million, which may be beyond G2 Corp.'s capacity as a first-time film producer.
### Explore Lower-Budget Options While Maintaining Success Potential:
If G2 Corp. prefers to work within more modest production budgets (under $55 million) while still aiming for success, it should still focus on drama, but in combination with genres such as action, crime, biography, sport, or romance. Writers who have achieved success within this budget range include Edgar Wright, Ethan and Joel Coen, Anthony McCarten, Steven Zaillian, Eric Johnson, Paul Tamasy, Taylor Sheridan, Simon Beaufoy, and Derek Cianfrance.

Films from these writers and genres can yield over $100 million in revenue with a typical budget of approximately $30 million.
Acknowledge the Creative Nature of Filmmaking:
It is important to recognize that movies are a creative process, and even with the correct combination of budget, writer, and genre, a film may not always meet expectations. External factors such as market conditions, audience preferences, and the quality of execution also play a significant role in a movie's success.



