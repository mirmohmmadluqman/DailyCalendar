1 Daily Calendar User Guide
Introduction
1 Daily Calendar is a modern, web-based calendar application designed to help you manage your daily tasks, track focus time, and organize notes efficiently. Whether you're scheduling events, setting reminders, or using the Pomodoro timer to boost productivity, this app has you covered. It supports both dark and light themes, is fully responsive for mobile and desktop use, and includes advanced features like data import/export, voice input for notes, and customizable settings.
This guide will walk you through setting up the application, using its features, and transitioning data for users migrating from the legacy version at 1dailycalendar.netlify.app to the new version at 1dailycalender.netlify.app.

Features

Calendar Views: Switch between Month, Week, and Day views to organize your schedule.
Note Management: Add, edit, pin, and categorize notes with options for color, priority, recurrence, attachments, and reminders.
Pomodoro Timer: Boost productivity with a timer that includes Pomodoro, Short Break, and Long Break modes, complete with an alarm sound.
Search Functionality: Quickly find notes by title, body, category, or date.
Statistics Tracking: Monitor your focus time and note activity with daily, weekly, and monthly reports.
Customizable Settings: Adjust font size, theme, language, high-contrast mode, reminder intervals, and timer durations.
Data Import/Export: Back up or restore your data, with support for legacy data from 1dailycalendar.netlify.app.
Voice Input: Add note details using voice (requires browser support and microphone access).
Responsive Design: Works seamlessly on desktops, tablets, and mobile devices.


Setup Instructions
Prerequisites

A modern web browser (e.g., Chrome, Firefox, Edge) with JavaScript enabled.
A local or hosted web server to serve the application files (e.g., using python -m http.server 8000 or a hosting service like Netlify).

Installation

Download the Files:

Clone this repository or download the ZIP file containing the application files.


File Structure:Ensure your directory matches the following structure:
/1-Daily-Calendar/
├── index.html           # Main application file
├── index2.html          # Placeholder for an external user guide (optional)
├── readme.md            # This user guide
├── Elements/
│   ├── myLogo.jpg       # Logo for favicon and notifications
│   └── alarm.mp3        # Alarm sound for Pomodoro timer


Host the Application:

Local Hosting:
Place the files in a directory.
Run a local server, e.g., using Python: python -m http.server 8000.
Open http://localhost:8000/index.html in your browser.


Online Hosting:
Deploy the files to a hosting service like Netlify (e.g., 1dailycalender.netlify.app).
Ensure the Elements folder is uploaded correctly.




Grant Permissions:

When prompted, allow notifications for reminders to work.
If using voice input, grant microphone access.




Using 1 Daily Calendar
1. Navigating the Calendar

Initial View:
The calendar defaults to the current month (e.g., May 2025 as of the system date, May 24, 2025).
Days of the week are displayed at the top, followed by the calendar grid.


Navigation:
Use the ◀ and ▶ buttons to move to the previous or next month.
Click Today to jump to the current date.
Toggle between Month, Week, and Day views using the 📅 button.


Special Days:
The current day is highlighted with a purple border.
Holidays (e.g., New Year's Day on 2025-01-01, Christmas on 2025-12-25) are highlighted in yellow.



2. Managing Notes

Adding a Note:
Click the floating + button at the bottom-right or click on a specific day in the calendar.
The note editor opens, showing the selected date.
Fill in the fields:
Title: A short title for the note (max 50 characters).
Details: The main body of the note.
Color: Choose a color to highlight the note in the calendar.
Category: Select Work, Personal, or Other.
Priority: Set as Low, Medium, or High.
Recurrence: Choose None, Daily, Weekly, or Monthly to repeat the note.
Attachment: Add a URL as an attachment (e.g., a link to a document).
Reminder: Set the number of minutes before the note’s date to receive a notification (set to 0 to disable).


Click Save to add the note to the calendar.


Editing a Note:
Click a day with an existing note to open the editor with the first note loaded.
Modify the fields and click Save.


Pinning a Note:
In the note editor, click 📌 Pin to prioritize the note (changes to 📍 Unpin).
Pinned notes appear at the top of the day’s note list with a highlighted background.


Voice Input:
Click the microphone button in the note editor.
Speak your note details, and the text will be appended to the Details field.
Requires a browser with Web Speech API support and microphone access.


Undo/Redo:
Use ↺ Undo and ↻ Redo to revert or reapply changes made in the note editor.


Sharing a Note:
Click 🔗 Share to copy the note’s title, body, and date to your clipboard.


Closing the Editor:
Click Close or click outside the editor on the overlay to close without saving.



3. Searching Notes

Search:
Enter a query in the search bar (located below the header with a gap for readability).
Search by title, body, category, or date (e.g., "Work", "2025-05-24").


View Results:
Click the 🔍 button to open a popup with search results.
Results show the date and note title.


Edit from Search:
Click a search result to open the note editor for that note.


Close Search:
Click Close or click outside the popup to close.



4. Using the Pomodoro Timer

Open the Timer:
Click the ⏰ button in the header to open the timer popup.


Select Mode:
Choose between:
Pomodoro (default: 25 minutes)
Short Break (default: 5 minutes)
Long Break (default: 15 minutes)




Control the Timer:
Click Start to begin.
Click Pause to pause, then Resume to continue, or Stop to reset.
When the timer ends, an alarm (Elements/alarm.mp3) plays, and it auto-switches modes (e.g., Pomodoro to Short Break).


Customize Durations:
Open the settings (⚙️) to adjust the durations for each mode.


Close the Timer:
Click Close or click outside to close the popup (this stops the timer).



5. Viewing Statistics

Open Statistics:
Click the 📊 button in the header.


View Reports:
Total Notes: Number of notes created.
Most Active Days: Days with at least one note.
Daily Focus Time: Focus time for each day.
Weekly Focus Time: Aggregated focus time per week.
Monthly Focus Time: Aggregated focus time per month.


Close Statistics:
Click Close or click outside to close the popup.



6. Customizing Settings

Open Settings:
Click the ⚙️ button in the header.


Adjust Options:
**



