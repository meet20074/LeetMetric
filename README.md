# LeetMetric
LeetMetric is a web-based tool designed to track and display your LeetCode progress in a visually appealing way. With LeetMetric, users can view their problem-solving statistics categorized by difficulty levels (Easy, Medium, Hard) and get an overall summary of their submissions.

# Features
User-Friendly Input: Enter your LeetCode username and fetch your statistics with one click.
Progress Visualization:
Displays the number of problems solved by difficulty (Easy, Medium, Hard).
Progress is represented using circular progress bars.
Dynamic Stats Cards: Provides a breakdown of the total submissions and attempts for each difficulty level.
Real-Time API Fetching: LeetCode stats are fetched in real time using GraphQL.
Responsive Design: Fully functional on desktop and mobile devices.

# Technologies Used
Frontend:
HTML5
CSS3
JavaScript (ES6+)
API: LeetCode GraphQL API
Proxy Service: https://cors-anywhere.herokuapp.com/ for CORS handling

# How It Works
Input: Enter your LeetCode username in the input field and click "Search."
Data Fetching: The app sends a GraphQL query to the LeetCode API via a proxy to retrieve problem statistics.
Data Processing:
Parses the total questions and solved questions across Easy, Medium, and Hard levels.
Dynamically updates progress bars and stats cards based on the fetched data.
Display: All results are displayed in an organized and visually appealing format.
