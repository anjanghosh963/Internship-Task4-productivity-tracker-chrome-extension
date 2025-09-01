Productivity Tracker - Chrome Extension
This project is a comprehensive Productivity Tracker Chrome extension designed to monitor, analyze, and report on your web browsing habits. It helps you understand where your time is spent and provides insights to improve your focus and productivity.

Features:
Time Tracking: Automatically tracks the time spent on each website.

Website Categorization: Classifies websites as 'Productive', 'Unproductive', or 'Neutral'.

Real-time Dashboard: A detailed dashboard to view your activity, including:

Today's productive vs. unproductive time.

A list of websites visited and time spent on each.

Analytics & Reports:

Weekly productivity breakdowns and scores.

Daily average time and session length.

Visual charts and graphs for daily trends.

Settings & Customization:

Set daily productivity goals.

Manage website categories.

Enable or disable notifications.

Popup Interface: A quick-access popup to see the current tracking status and daily stats without opening the full dashboard.

Inactivity Detection: Pauses tracking automatically when you are inactive to ensure accurate data.

Data Export: Export your productivity data in JSON format.

Project Structure:
.
├── manifest.json       → Extension configuration file
├── popup.html          → The HTML for the main dashboard and popup interface
├── popup.js            → Core JavaScript logic for the extension's UI and features
├── background.js       → Service worker for background tasks (e.g., tracking time, tab changes)
├── content.js          → Injected into web pages to detect user activity/inactivity
└── README.md           → Project documentation (this file)
How to Install and Run:
Since this is an unpacked Chrome extension, you need to load it manually in Developer Mode.

Download or Clone the Repository: Get all the project files onto your local machine.

Open Chrome Extensions: Open Google Chrome and navigate to chrome://extensions.

Enable Developer Mode: In the top-right corner, toggle the "Developer mode" switch to 'On'.

Load Unpacked:

Click on the "Load unpacked" button that appears on the top-left.

Select the directory where you saved the project files.

Done! The "Productivity Tracker" extension will now appear in your extensions list and in the Chrome toolbar.

Tech Stack Used:
HTML5

CSS3 (with modern Flexbox and Grid layouts)

JavaScript (Vanilla)

Chrome Extension APIs (Storage, Tabs, Runtime, etc.)

Author:
Anjan Ghosh
Full Stack Web Development Intern
CodTech IT Solutions

License:
This project is open-source and available under the MIT License.