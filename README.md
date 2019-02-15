# The Hive - Buzz Around Town
### Overview
This project is a mobile-responsive web application named The Hive. The concept of the app is to aggregate relevant local content for new residents of cities throughout the United States. A user creates an account and fills out their profile information. The webpage then displays recommendations based on their location and interests. 
### How It Works
This application uses firebase authentication to create accounts and store each user's associated profile information in a realtime database. The Giphy api is used to generate a user avatar which is displayed on their profile page. A proxy server is used to make ajax calls to both Google Places and MeetUp APIs. Using JavaScript and jQuery the top 3 local results for each of the user's interests is dynamically displayed in their profile page. The user can update their information via a settings page if they wish. 
### How To Use The Hive
To use The Hive you must first set up an account by providing a valid email address and creating a minimum six-character password. Some personal information is also required to set up an account: first name and zipcode are required. Once your account has been created you will be taken to an interests page where you can select some personal and professional topics that you would like to engage with in your local community. These selections allow The Hive to customize your recommendations. Once you have selected some interests your profile is generated with personalized content recommending places for you to explore in your city.
### Join The Hive
If you're ready to start buzzing around your town then check out the app on [heroku](https://thehivebuzz.herokuapp.com/). You can create your own account or login using the guest account as follows:
**Email**: guest@thehive.com
**Password**: 111111
