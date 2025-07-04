# Mood-Diary

📔 Mood Diary Application
This is a simple, client-side web application designed to help users track their daily moods and reflections. It provides an intuitive interface for logging feelings, viewing mood trends over time, and reflecting on past entries.

Features
Daily Mood Entry: Easily log your mood using emojis and add a descriptive note about your day.

Dynamic Reflection Prompts: Get a new journaling prompt each day to encourage deeper self-reflection.

Mood Calendar: Visualize your mood history on an interactive calendar, with color-coded days representing your emotional state.

Mood Trends Chart: See graphical representations of your mood over the last 7 days, current month, or all time.

Reflection Mode: Review your past entries and prompts to identify patterns and gain insights into your emotional well-being.

Dark Mode Toggle: Switch between light and dark themes for comfortable viewing.

Data Management: Export your mood data to a JSON file for backup, or import data to restore your entries.

Daily Reminders: Set a daily notification time to remind you to log your mood.

Privacy Lock (PIN protection): Secure your diary entries with a customizable PIN.

Technologies Used
HTML5: Structure of the web application.

Tailwind CSS: Utility-first CSS framework for rapid and responsive styling.

JavaScript (ES6+): Core logic, interactivity, and data management.

Chart.js: For rendering interactive mood trend graphs.

Local Storage: Used for persistent storage of mood entries, settings (dark mode, reminder time, PIN), and lock status directly in the user's browser.

How to Use
Open the Application: Simply open the index.html file in your web browser.

Daily Entry:

Select an emoji that best represents your mood.

Write a note in the text area about why you're feeling that way.

Click "Save Mood" to record your entry. If you've already made an entry for the day, "Edit Mood" and "Delete Entry" buttons will appear.

Navigate Tabs: Use the navigation buttons (Daily Entry, Calendar, Trends, Reflection, Settings) to switch between different views of your mood diary.

Calendar: Browse through months to see your past mood entries. Hover over a day with an entry to see a quick summary.

Trends: View line graphs showing your mood fluctuations over different periods.

Reflection: See a list of your recent mood entries and the prompts that accompanied them.

Settings:

Dark Mode: Toggle the switch to change the application's theme.

Data Management: Use "Export Data" to download your entries or "Import Data" to load a previously saved JSON file.

Daily Reminder: Enable the reminder, set a time, and grant notification permissions to receive daily prompts.

Privacy Lock: Enable the lock and set a 4-digit PIN to secure your diary. You will be prompted for this PIN when accessing the app.

Data Storage
All your mood entries and settings are stored locally in your browser's localStorage. This means your data is private and remains on your device. However, it also means that clearing your browser's data (cache, cookies, local storage) will delete your mood diary entries unless you have exported them.

Future Enhancements (Ideas)
Cloud synchronization (e.g., Firebase, IndexedDB for larger local storage).

More detailed analytics and custom date range selection for trends.

Categorization of notes (e.g., work, personal, health).

Tagging system for entries.

Sentiment analysis on notes.

Customizable reminder messages.

Password recovery for PIN.

PWA (Progressive Web App) features for offline access and installability.
