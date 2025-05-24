1 Daily Calendar
Overview
1 Daily Calendar is a web-based calendar application designed to help users manage their daily tasks, notes, and focus time. It includes features like a Pomodoro timer with an alarm, note management with recurrence, search functionality, statistics tracking, and customizable settings. The application supports both dark and light themes and is fully responsive for use on various devices.
Setup Instructions

Clone or Download the Repository:

Clone this repository or download the files to your local machine.


File Structure:Ensure the following files are in place:
/1-Daily-Calendar/
├── index.html           # Main application file
├── index2.html          # User Guide (placeholder, not provided)
├── readme.md            # This file
├── Elements/
│   ├── myLogo.jpg       # Logo for favicon and notifications
│   └── alarm.mp3        # Alarm sound for Pomodoro timer


Host the Application:

Place all files in a web server directory (e.g., using XAMPP, WAMP, or a simple HTTP server via Python: python -m http.server 8000).
Ensure the Elements folder is in the same directory as index.html with the correct files (myLogo.jpg and alarm.mp3).


Open in Browser:

Open index.html in a modern web browser (Chrome, Firefox, or Edge recommended).
Grant notification permissions when prompted for reminders to work.



Usage

Calendar View:

Navigate months using the ◀ (previous) and ▶ (next) buttons.
Click Today to jump to the current date.
Toggle between Month, Week, and Day views using the 📅 button.
Days with notes are displayed; click a day to add or edit notes.


Notes:

Click the + floating button or a calendar day to open the note editor.
Add a title, details, color, category, priority, recurrence, attachment URL, and reminder.
Use the microphone button for voice input (browser support required).
Pin notes to prioritize them, undo/redo changes, and share notes via clipboard.


Search:

Use the search bar to find notes by title, body, category, or date.
Click the 🔍 button to view results in a popup and select a note to edit.


Pomodoro Timer:

Open the timer via the ⏰ button in the header.
Choose between Pomodoro, Short Break, and Long Break modes.
Start, pause, resume, or stop the timer. An alarm (Elements/alarm.mp3) plays when the timer ends.
Customize durations in the settings.


Settings:

Access settings via the ⚙️ button in the header.
Adjust font size, theme, language, high-contrast mode, reminder interval, and timer durations.
Import/export data as JSON to back up or restore your calendar.


Statistics:

View focus time and note statistics via the 📊 button in the header.



File Structure

index.html: The main application file containing HTML, CSS, and JavaScript.
index2.html: Placeholder for a user guide (not implemented).
readme.md: Documentation for setup and usage.
Elements/:
myLogo.jpg: Logo used for the favicon and notifications.
alarm.mp3: Alarm sound played when the Pomodoro timer ends.



Notes

Ensure Elements/myLogo.jpg and Elements/alarm.mp3 are present for the application to function fully.
The application uses localStorage to save notes, focus data, and settings.
Voice input requires a browser with Web Speech API support and microphone access.
High-contrast and custom theme options (blue, green) require additional CSS to be fully functional.

