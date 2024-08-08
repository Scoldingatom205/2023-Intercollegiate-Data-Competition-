# TripAdvisor Analysis - Project Overview
1 of 12 teams to compete in Intercollegiate Datathon @ Alteryx in December 2023.
My team took 4th place and awared Judge's Choice Award!

## Business Question: How can hotels predict a TripAdvisor review, and what amenities should hotels prioritize in order to ensure the highest review?

### Dataset Structure
We were given an excel file filled with Las Vegas Hotels TripAdvisor data. Includes details about users, hotels, and reviews. The data was organized in chronological order
according to period of stay column and alphabetical order for hotels. Each hotel has 24 users where each row represents one user.
![image](https://github.com/user-attachments/assets/1cd7cba1-07b3-4efb-951c-ba4bb40f5018)

### Insights Summary
The business question wanted to address two KPI's:
  - **Number of Hotel Reviews:** Tripadvisor collects all reviews left by user. The (Nr. hotel reviews) column is the aggregate of only hotel reviews left by that user.
  - **Score:** The average score of all hotel scores the user has every given.

**Number of Hotel Reviews**
- **Weekday:** Saturday and Sunday had the highest amount of hotel reviews (combined 35% of total) and customers leave roughly 25% more hotel reviews on average on Sat and Sun. 
- **Review Month:** August, and September receives roughly 44% more hotel reviews on average than the rest of the months combined. 
- **Traveler Type:** Although Couples have left the highest number of hotel reviews, Business travelers by far leave the most on average (40% more)!
Be wary thought because business travelers are the most critical leaving the lowest scores out of all traveler types.
- **Continent:** Although North America had the highest number of hotel reviews, Asia on average leaves about 25% more hotel reviews
- **Hotel Stars:** Notably, hotels with 3.5 or 4.5 stars have the highest hotel reviews on average although only making up about 25% of all hotel reviews.
- **Amenities:** Similarly to the boxplots, no pool drops hotel reviews by 50%. If we want to increase hotel reviews by 35-45% exclude spa, gym and (to my surprise) casino.

**Score**
- **Weekday:** Saturday and Friday received on average higher review scores. 
- **Review Month:** Despite having one of the lowest total number of reviews, March has the highest review score.
Among the highest reviewed, Aug comes in with the second highest reviews score.
- **Traveler Type:** Friends and Couples leave the highest review scores at 4.25 (avg = 4.12).
- **Period of Stay:** Those that stay between Dec-Feb leave the highest review scores.
- **Continent:** Despite Asia being very active in leaving reviews they leave the second lowest scores. South America on the other hand, leave the highest scores with 4.43 (avg = 4.12).
- **Hotel Stars**: To no surprise, 5 star hotels receive the highest review scores but 3.5 star hotels receives the second highest.
- **Amenities:** Having certain amenities influence reviews score but a stronger influence are when amenities are excluded!
When pool is excluded 77% decrease in average score. When free internet is excluded 80% decrease in average score. Gym sees about 1% decreases when excluded.
Spa and Tennis court are interesting because excluding it drops scores by a <1% but including increases scores by 1% and 3% respectively.

### Recommendations
**1. Maximize Review Volume:** Encourage Saturdays and Sundays stays as they generate 35% of total reviews, with customers leaving 25% more reviews on average. Focus on Peak Months, August and September, as they see a 44% increase in reviews. Especially August.

**2. Target High-Impact Traveler Segments:** Like Business Travelers who leave 40% more reviews on average but be careful as they leave lower scores. Couples and Friends are a quiet pick as they leave higher scores and just a few more reviews on average.

**3. Capitalize on High-Performing Regions:** Although North America and EU leads in review volume, focus on strategies to attract travelers from Asia, who leave 25% more reviews on average. Develop tailored experiences for South American guests as they leave the highest scored reviews but are among the lowest review givers.

**4. Optimize Hotel Star Rating:** Promote 3.5 and 4.5-Star Hotels as these hotels yield the highest average review volume. Consider strategies to enhance hotels standing in these categories. As for 5-Star Hotels, they can continue delivering great service as they lead in review scores but fall behing on review volumn. They can encourage visitors to leave more reviews!

**5. Prioritize Essential Amenities and Reconsider Other Amenities:** Ensure Pool and Free Internet are always available! Excluding these amenities drastically lowers scores (up to 80% decrease) but increase reviews significantly. Spa and Tennis Court on the other hand, have minimal impact, but consider their inclusion based on overall guest experience rather than score alone.

**6. Maintain Quality Service Year-Round:** Hotels can Capitalize on the higher scores received between December and February to boost off-season occupancy and ratings. Perhaps offer special promotions for stays between Dec-Feb and target Friends and Couples for high scores.



