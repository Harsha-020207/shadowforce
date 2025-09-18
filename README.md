The Facts Time – News Portal Website

The Facts Time is a responsive, interactive newspaper website built with HTML, CSS, and JavaScript. It features a dynamic news feed, category navigation, and user authentication overlays for login and registration.

Features

Responsive Layout: Works on desktops, tablets, and mobile devices.

Top Navigation Menu: Includes news categories – Business, Climate, Crime, Movies, Sports.

Dynamic News Feed: Fetches news from GNews API
 and displays articles with images, descriptions, and content expansion.

Login & Registration Overlays:

Login and Register buttons are located on the top-right corner.

Overlays appear automatically if the user is not logged in within 5 seconds.

Users can log in or register to personalize the experience.

Interactive UI:

Read More/Show Less buttons to expand article content.

Previous/Next navigation for news tabs.

Local Storage Login State: Stores the username temporarily to display the welcome message after login.

Clean Design: Styled with modern, minimalist design and smooth hover effects.

Technologies Used

HTML5 – For the structure and layout.

CSS3 – For styling, responsive layout, and overlays.

JavaScript – For dynamic behavior, login/register handling, and API requests.

GNews API – Fetches real-time news articles for different categories.

Installation

Clone the repository:

git clone https://github.com/yourusername/the-facts-time.git


Navigate to the project directory:

cd the-facts-time


Open the index.html file in a browser:

open index.html
# or simply double-click the file

Usage

Upon opening the website, you will see the homepage with news categories.

If you are not logged in, a login/register overlay will automatically appear after 5 seconds.

Use the Login or Register buttons in the top-right corner to log in or create an account.

Navigate through news categories using the menu buttons.

Use Previous and Next buttons to switch between tabs.

Click Read More on each article to view the full content.

Folder Structure
the-facts-time/
│
├── index.html       # Main HTML file
├── README.md        # Project documentation
├── style.css        # (Optional) External CSS if extracted
├── script.js        # (Optional) External JS if extracted
└── assets/          # Images/icons if used

API Configuration

The site uses the GNews API
 to fetch news articles.

Replace the apiKey variable in script with your own GNews API key for production:

const apiKey = "YOUR_API_KEY_HERE";

Contributing

Fork the repository.

Create a new branch: git checkout -b feature/YourFeature

Make your changes and commit: git commit -m 'Add some feature'

Push to the branch: git push origin feature/YourFeature

Create a Pull Request.

License

This project is licensed under the MIT License. See the LICENSE
 file for details.
