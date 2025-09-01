# 🎯 Internship-Task4-productivity-tracker-chrome-extension

A comprehensive Chrome extension designed to monitor, analyze, and report on your web browsing habits to boost productivity. This tool helps you understand where your time is spent online and provides insights to improve your focus.


---

## ✨ Core Features

-   ⏰ **Time Tracking**: Automatically tracks the time spent on each website.
-   🗂️ **Website Categorization**: Classifies websites as 'Productive', 'Unproductive', or 'Neutral'.
-   🖥️ **Real-time Dashboard**: A detailed dashboard to view your activity, including productive vs. unproductive time for the day.
-   📈 **Analytics & Reports**: Provides weekly productivity breakdowns, scores, and visual charts for daily trends.
-   ⚙️ **Customization**: Manage website categories and set daily productivity goals.
-   👆 **Quick Access Popup**: See the current tracking status and daily stats without opening the full dashboard.
-   😴 **Inactivity Detection**: Automatically pauses tracking when you are inactive to ensure data accuracy.
-   💾 **Data Export**: Export your productivity data in JSON format.

---

## 🛠️ Tech Stack

-   **Frontend**: HTML5, CSS3 (Flexbox & Grid), Vanilla JavaScript
-   **Platform**: Chrome Extension APIs (Storage, Tabs, Runtime)

---

## 📂 Project Files

All the necessary source code for the extension is located in the **`Task4/`** directory in this repository.

Alternatively, I've attached the Task 4 files in a `Task4.rar` archive. You'll need to extract the archive to access the complete folder.

---

## 🚀 Getting Started: How to Install

To install and run this extension locally, follow these steps:

1.  **Download the Code**: Clone this repository or download the files, preferably from the `Task4/` folder.
2.  **Open Chrome Extensions**: In your Chrome browser, navigate to `chrome://extensions`.
3.  **Enable Developer Mode**: Find the "Developer mode" toggle in the top-right corner and turn it on.
4.  **Load the Extension**:
    -   Click the "Load unpacked" button.
    -   Select the **`Task4`** folder that you downloaded.
5.  **Done!** 🎉 The Productivity Tracker extension should now appear in your browser's toolbar.

---

## ⚙️ How It Works

The extension's logic is split across several key files:

-   **`manifest.json`**: The core configuration file that tells Chrome how the extension works.
-   **`popup.html`**: Provides the HTML structure for the main dashboard and the quick-access popup interface.
-   **`popup.js`**: Contains the JavaScript logic for the user interface, handling user interactions and displaying data.
-   **`background.js`**: A service worker that runs in the background to manage time tracking, monitor tab changes, and handle core logic.
-   **`content.js`**: A script injected into web pages to detect user activity (like scrolling or typing) to determine if you are active or inactive.


---

## 📸 Screenshots
*Here you can add a screenshot of your extension's main dashboard or popup.*

<img width="433" height="697" alt="Task-4-1" src="https://github.com/user-attachments/assets/678ba393-97b9-4f82-8625-8ff7536cb56f" /> <img width="405" height="672" alt="Task-4-2" src="https://github.com/user-attachments/assets/9369a351-c9cc-4dcf-92d8-e8bcfeb4afe4" />

<img width="1920" height="1031" alt="Task-4-3" src="https://github.com/user-attachments/assets/74b80189-c377-46a6-82df-deb42409c03c" />

<img width="1920" height="1029" alt="Task-4-4" src="https://github.com/user-attachments/assets/14721964-0202-4e93-8d41-3cdd41442fc8" />

<img width="1920" height="1032" alt="Task-4-5" src="https://github.com/user-attachments/assets/1aadb540-188b-4edf-9075-00c7fbfb19de" />
