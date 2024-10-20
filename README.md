# ANNA
ANNA - A Seamless Food Donation Platform

Project Overview:
Anna is a food donation app built on Java and powered by Firebase. Its primary objective is to facilitate the process of food donation, connecting food donators with receivers in a seamless manner. With Anna, we can contribute to reducing food waste and helping those in need by donating surplus food items.

Objectives:
1.	Reduce Food Waste: Create a platform where surplus food can be donated rather than discarded, minimizing food waste.
2.	Facilitate Food Access: Provide an easy-to-use interface that connects food donators with receivers, ensuring that food reaches those in need.
3.	Enhance Community Engagement: Foster a sense of community by encouraging users to contribute to a cause that benefits local people facing food insecurity.
4.	Data-Driven Insights: Offer a history tracking feature to provide insights into donation patterns, allowing users to see their impact over time.

Target Audience:

•	Individuals and Families: People who have surplus food and wish to donate it to others in need.
•	Non-Profit Organizations: Community groups and food banks looking to streamline food distribution efforts.
•	Students and Social Workers: Those involved in community outreach and support programs.

Key Features:

1.	User Registration and Authentication:

•	Users can sign up using their email, create a strong and secure password, and provide personal details like name and phone number.

•	Email Verification is implemented using a verification link sent to the user’s email to ensure authenticity and security.

•	Users can opt for Two-Factor Authentication(2FA) for an added layer of security.

2.	User Login and Authentication:

•	Users can login using their email, and password.

3.	Dashboard

•	User can view all features of the app such as Donate, Receive, Food Map, Remove My Pin, History, My credentials, Settings, Logout and etc.

4.	Food Donation Process:

•	In the "Donate" section of the app, we can easily pin our location on the map to indicate the availability of food donations. The following information is required when creating a food pin:
	Food Item Name: Specify the name of the food item we wish to donate(e.g. "Vegetable Soup," "Rice and Chicken").
	Food Item Description: Provide a brief description or additional details about the donated food(e.g. "Freshly cooked, serves 4 people, vegetarian").
	Phone Number Visibility: Choose whether or not we want to display our phone number to receivers. If we choose to hide our phone number, Anna can facilitate communication through a temporary masked number, allowing secure interactions without revealing our personal contact information.

•	Users can pin their location on an interactive map to indicate the availability of food donations.

•	Users can choose to display their phone number or use temporary masked numbers for secure communication without revealing their actual contact information.
Note: Anna does not have an in-app messaging feature. If we choose to display our phone number, it will only be visible to receivers.

5.	Food Receiving Process:

•	In the "Receiver" activity, users can find food pins near their location. By clicking on a specific food pin, they can access detailed information about the donation including food item descriptions, photos, quantity, and availability times.

•	Receivers have the option to navigate to the donator's residence using the Google Maps. This feature helps receivers easily collect the donated food.

•	After the food has been successfully picked up, the donator has the option to remove their pin from the map, keeping the available listings up-to-date and accurate for other users. This streamlined process ensures efficient communication and a hassle-free experience for both donators and receivers.

6.	Real-Time Food Map:

•	The Food Map Activity shows all available food pins on a real-time map, allowing users to explore nearby donations.

•	Users can click on pins to view detailed information about each donation. Advanced Filters enable users to sort food pins based on distance, food type, or freshness.

•	Note that, the phone number of the donator will not be displayed in this activity. It is only visible in the "Receiver" activity.

7.	Donation History:

•	The "History" activity in Anna keeps track of all our past food donations. It displays a list of our previous donations, including food item names, descriptions, photos, donation dates, and pickup details.

•	Users can easily review their donation history, filter records by date or type of food, and export donation summaries for personal reference or community impact reports .

•	Individual donation records can be deleted if needed, offering users full control over their data. This feature allows users to reflect on their positive impact while keeping their records organized and up-to-date.

8.	Remove Food Item Pin

•	After the food has been successfully picked up, the donator can remove their pin from the map, keeping the available listings up-to-date and accurate for other users. This streamlined process ensures efficient communication and a hassle-free experience for both donators and receivers.

9.	Update Profile:

•	Reset Password: Users can reset forgotten passwords through a secure email-based recovery process.

•	Profile Management: Users can update their email, name, and phone number directly from the app settings.

•	Profile Customization: Users can upload a profile picture to add a personal touch to their profile.

10.	Delete Profile

•	Users can delete their whole profile from this app if they want.

11.	Search and Filters

•	Users can search foods according items name, location etc.

12.	Ratings and Reviews

•	Users can give ratings and reviews as feedback in the app.

13.	User Support and Help

•	Help Section: FAQs and support information.

•	Report Issues: Functionality to report issues or inappropriate behavior within the app.

Technology Stack:

•	Frontend: Java (Android Development), XML for UI design.

•	Backend: Firebase for authentication, real-time database, and storage.

•	APIs: Google Maps API for geolocation and navigation.

•	Authentication: Firebase Authentication for secure login and user verification.


Implementation Plan:
1.	Phase 1: Design and Planning:

•	Finalize the app’s UI/UX design and create wireframes for each activity.

•	Define database structure and Firebase integration requirements.
2.	Phase 2: Development:

•	Implement user registration, authentication, and email verification.

•	Develop the Donate and Receiver activities with Google Maps integration.

•	Integrate the Food Map with real-time updates and advanced filtering.

•	Implement the History Activity and export functionality.
3.	Phase 3: Testing:

•	Conduct thorough testing of user registration, food donation, and map navigation features.

•	Perform User Acceptance Testing (UAT) to gather feedback and refine the app.
4.	Phase 4: Deployment:

•	Deploy the app on the Google Play Store for Android users.

•	Create marketing materials to promote the app and encourage community participation.
5.	Phase 5: Maintenance and Updates:

•	Monitor app performance and address any bugs or issues.

•	Introduce new features based on user feedback, such as in-app messaging or social media sharing.

Expected Outcomes:

•	A fully functional and user-friendly food donation app that bridges the gap between food donators and receivers.

•	Reduction in food waste and improved access to food for those in need.

•	Enhanced community engagement through increased awareness and participation in food donation activities.

Conclusion:
The Anna App aims to make food donation more accessible, organized, and efficient by leveraging modern technology to connect donors with those in need. Through a seamless user experience, real-time updates, and secure interactions, Anna empowers communities to make a positive impact by reducing food waste and supporting those facing food insecurity. With this proposal, we seek to create a sustainable solution that brings communities closer while addressing a critical social issue.




