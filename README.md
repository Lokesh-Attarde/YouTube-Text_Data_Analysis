
# Sentiment Analysis: YouTube - Text Data Analysis Project 🔥🍁

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/Lokesh-Attarde/YouTube-Text_Data_Analysis)
  ![GitHub forks](https://img.shields.io/github/forks/Lokesh-Attarde/YouTube-Text_Data_Analysis)
  [![GitHub contributors](https://img.shields.io/github/contributors/Lokesh-Attarde/YouTube-Text_Data_Analysis.svg)](https://GitHub.com/Lokesh-Attarde/YouTube-Text_Data_Analysis/graphs/contributors/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
</p>  

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/141673300-262b9d9f-58b8-4a53-b9a2-e950a02bf070.gif">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/141673294-97ec4e38-baf0-456a-ad92-995eac45be97.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/141673198-7537b494-ed5d-43c0-baa3-db22f80ca04a.jpg">
</p>

# 📝Problem Statement

Analysis of the following is required by the Sales Team of Hotel Bookings:

    1. Analyze from which Country most guests come?
    2. Country-wise Guests distribution.
    3. Price of Room Types per Night.
    4. How does the Price per Night vary over a Year?
    5. Distribution of Nights Spent at Hotels by Market Segment and Hotel Type.
    6. Preference of Guests in terms of Meal's.
    7. Relationship between Special Requests and Cancellation.
    8. Which are the Most busiest Months throughout a Year.
    9. How long do People Stay at the Hotels?
    10. Price per Night w.r.t. Market Segment and Room Type.
    11. Distribution w.r.t. Cancellation of Bookings.
    12. Which Month have the Highest Number of Cancellations?

And many more!!

# ⏳ Dataset
Download the dataset for this project from following Link -
* [YouTube - Text Data Analysis Dataset](https://drive.google.com/drive/folders/1L7EAm3cqvDwgiyOuRAuZeUazBKVU-syp?usp=sharing)

# 📚 Data Analysis
In the datasets, we are provided with 32 columns(Features) of data.

* **hotel** : Hotel (H1 = Resort Hotel or H2 = City Hotel)
* **is_canceled** : Value indicating if the booking was canceled (1) or not (0).
* **arrival_date_year** : Year of arrival date.
* **arrival_date_month** : Month of arrival date.
* **stays_in_weekend_nights** : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
* **stays_in_week_nights** : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
* **adults** : Number of adults.
* **children** : Number of children.
* **babies** : Number of babies.
* **meal** Type of Meal booked. Categories are presented in standard hospitality meal packages.
* **country** : Country of Origin. Countries are represented in the ISO 3155–3:2013 format.
* **market_segment** : Market segment designation. In categories, the term "TA" means "Travel Agents" and "TO" means "Tour Operators".
* **reserved_room_type** : Code of room type reserved.
* **adr** : Average Daily Rate / Price per night.
* **total_of_special_requests** : Number of special requests made by the customer.

Out of the 32 features given in the datasets, 20 are Continuous and 12 (including the target variable) are Categorical features.

# 🖥️ Technologies:
## 🛠️ Tools Used
* Jupyter Notebook is used as IDE.
* Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* GitHub is used as version control system.

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/141269995-77714aa7-9b0c-4b11-a94c-e1639a0a743b.png">
</p>

# 🎉 Tasks performed under Choropleth Maps Analysis:
* Analysed ***Countries with most guests come from*** using **'Choropleth Maps'**.
* Moreover, Plotted a **"Choropleth Maps with Animation"** for in-depth analysis on Yearly basis.

# 🌱 Some Exciting Glimpse of the Visuals:
![Final Glimpse 1](https://user-images.githubusercontent.com/84115928/141301079-637277f2-a00f-4808-9c38-594b22756412.gif)
![Final Glimpse 2](https://user-images.githubusercontent.com/84115928/141341458-ef8881a7-70b4-4db5-b57e-b3d5795d184b.gif)
![Final Glimpse 4](https://user-images.githubusercontent.com/84115928/141303002-feaed86b-ba9c-4911-8b08-7b54317a59ef.gif)

# 💡 Conclusions
* In terms of "Resort Hotel", "PRT" is dominated by around "35.2%" of Guests followed by "GBR" and "ESP" having "20.5%" and "10.7%" of guests respectively.
* "PRT" (Portugal) has the Maximum Number of Guest of around '21.071K' followed by "GBR" (United Kingdom) I.e. UK and "FRA" (France) having '9.67K' and '8.48K' Number of Guests respectively.
* There is a significant rise of Number of Guests in terms of "PRT", "GBR", and "FRA" from the Year 2015 to 2016. However, again in the Year 2016 to 2017, the Number of Guests proportion has declined rapidly.
* "A" Category Room, are having Highest Price approx. '500 EUR'. Whereas with respect to this "G" Category Room as well, will see that 'City Hotel Rooms' are Much 'Costlier' than All other Rooms.
* "Resort Hotel Prices" are much Higher during the 'Summer', whereas at the same time, "Prices" of a "City Hotel" doesn't varied that much.
   On the other hand, "City Hotels" are Expensive during the 'Spring' or 'Autumn' Season (i.e. In 'May' and 'August').
* Almost "77.3%" of the Bookings are definitely prefer 'Bed & Breakfast'. Secondly, 'Half Board' (Breakfast and Dinner) kind of Meal's were prefered by around "12.1%" of guests and "8.92%" of guests prefer 'Self-Catering' (No Meals) kind of Bookings.
* Most of the Customers are not made any kind of 'Special Requests'.
   Or Almost "50%" of the Bookings don't have any kind of 'Special Requests'.
* In terms of "City Hotel", We have More Guests during the 'Autumn' & 'Spring' Season when the Prices are also 'Highest'. 
    * Whereas In terms of our "Resort Hotel", the 'Most busiest Month' is "August" followed by "July" & "October".
    * In a Nutshell, Will can say, both the Hotels have the Fewest Guests during the "Winter" (i.e. Jan, Nov & Dec) And although Prices are also Lower.
* Majority of People are prefer to Stay in the "City Hotel", mostly for '3' Nights. It might because of the "Prices" of a "City Hotel" doesn't varied much when we compared it with "Resort Hotel".
* "Online TA" is going to Dominate on each and every Category of Market Segment by '47.5%'. We can also say that, Almost "50%" of the Bookings are takes place in this "Online" way.
* Almost "75%" of Cancel Bookings are with respect to our "City Hotel, whereas "25%" are with respect to our "Resort Hotel Bookings".
* "August" Month has the Highest Number of Cancellations followed by "July" & "May".

And so many more!!

# 🎉 Help Me Improve
Hello Mr. Reader, if you find any bug or anything else that could add more value in this project then please consider raising it to me I will address them asap.
  
# 📫 Feedback
If you have any feedback, please reach out to me via [LinkedIn](https://www.linkedin.com/in/lokesh-attarde-145086141/)
