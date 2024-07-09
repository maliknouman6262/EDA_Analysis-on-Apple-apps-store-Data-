# EDA_Analysis-on-Apple-apps-store-Data-
7.0 Summary
The EDA exercise conducted on the Apple App Store dataset has yielded numerous interesting insights. The dataset was found to be relatively clean and consistent throughout the analysis. We posed several questions to the dataset and provided detailed answers and findings as follows:

Q1. What are the top 10 categories with the most downloads from the Apple Store?
A1: Gaming apps are the most downloaded apps from the store.

Q2. What are the top 10 primary genres with the highest average user rating?
A2: The highest rated primary genres based on average user rating are Weather, Games, Photo & Videos, Music, Books, and References, among others.

Q3. Which primary genre has the highest count of paid and free apps?
A3: The list of free apps includes Games, Business, Education, Utilities, and Lifestyle, while the list of paid apps includes Education, Games, Utilities, Stickers, and Productivity.

Q4. What are the top 5 paid apps with the highest ratings?
A4: The top 5 paid apps with the highest ratings are Super Nano Trucks, FarRock Dodgeball, Money Easy - Expense Tracker, Money Flow - Expense Tracker, and Sketch Ideas.

Q5. What are the top 5 free apps with the highest ratings?
A5: The top 5 free apps with the highest ratings are Rise of Zombie - City Defense, Dog Wheelchairs, Dog App - Breed Scanner, Dojo Login 2, and Dojo Hero.

Q6. What are the apps with the highest content rating?
A6: The apps with the highest content rating are for children, adults, teens, and everyone, with a breakdown based on the count of apps under each category.

Q7. In which years were the most apps released?
A7: The year 2020 saw the highest number of app releases, likely due to the COVID-19 pandemic and more people staying at home.

Q8. How does the size of an app in MBs compare to its price?
A8: We tried to find a correlation between app size and price but found that, except for a few exceptions, the size of the app is irrelevant to the price.

Q9. Who are the top 10 app-producing developers?
A9: The top 10 app-producing developers are ChowNow, Touch2Success, Alexander Velimirovic, MINDBODY, Incorporated, Phorest, OFFLINE MAP TRIP GUIDE LTD, Magzter Inc., ASK Video, RAPID ACCELERATION INDIA PRIVATE LIMITED, and Nonlinear Educating Inc.

Q10. What types of genres attract which types of clients in terms of revenue?
A10: Some interesting points need further analysis and attention, such as what kind of Business & Utilities apps are bought by or for children. It was found that the information stored in the content rating attribute is not very reliable and that there is a possibility that an app is rated for 9+ but is actually an e-book with unsuitable topics.

Q11. How do app releases per content rating compare year on year?
A11: Clearly, the children's category is taking the lead, but as pointed out earlier, the content rating of non-kids apps is also rated under the children's category.

Q12. How does user rating compare to price?
A12: The higher the user rating, the higher the price of the app.

Q13. How does user rating compare to MB size?
A13: The higher the user rating, the larger the size in MB of the app.

Q14. How do YoY breakdowns per genre based on app price compare?
A14: Educational apps contribute more revenue in terms of app sales.

Q16. Interdependency of numeric attributes on each other
Answer 16: Few attributes show strong dependence on each other, except for Average_User_Rating and Current_Version_Score.

Conclusion & Findings
The primary goal of this project is to analyze the Apple App Store dataset and identify insights based on the data. By doing so, we aim to project customer dynamics and demands to developers and relevant stakeholders, helping them generate more business for their upcoming applications.
During this EDA exercise, we have achieved several milestones:

We have cleaned the dataset from null values.
No duplications have been found. Although the app names have duplications, they are unique records with different versions, AppIds, and release dates.
Our findings include:

Gaming apps are the most downloaded apps from the store.
The top 10 highest rated primary genres based on average user ratings are Weather, Games, Photo & Videos, Music, and Books.
It is important to note that the information stored in the content rating attribute may not always be reliable. There is a possibility that an app rated for 9+ may contain unsuitable topics, such as e-books:)
