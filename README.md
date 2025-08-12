# Daily-Calendar-Summary-Notifications-via-Telegram-from-Google-Calendar
This n8n workflow sends you a daily 7 AM Telegram message with all your Google Calendar events for the day. It lists event names, times, locations, and notes, or tells you there are no events. Perfect for staying organized with Google Calendar and Telegram. Requires Telegram bot token and Google account.


## Context:
This workflow automatically sends you a daily message on Telegram summarizing all your meetings and events for the day, straight from your Google Calendar.

## For who ?
Perfect for anyone who:

- Uses Google Calendar to manage their schedule.
  
- Wants Telegram reminders for daily events.
- Loves automation and productivity tools.
- Requirements:
- Telegram.
- Google account.
- Google Calendar.


Steps:

<img width="1259" height="656" alt="image" src="https://github.com/user-attachments/assets/2f311512-7981-461a-b5db-80e07519c41f" />



🗒️ Use the sticky notes in the n8n canvas to:

- Add your Telegram and Google credentials.
- Execute and test the workflow.
- Check if you receive your daily summary on Telegram.
  

You'll get this:


<img width="450" height="675" alt="image" src="https://github.com/user-attachments/assets/1165eede-1bad-41a9-b386-e89a67685c33" />




<img width="470" height="567" alt="image" src="https://github.com/user-attachments/assets/b4345ba9-faa4-4455-972d-e98f47806e4c" />



Tutorial video:

[Watch the Youtube Tutorial video
](https://www.youtube.com/watch?v=eIELi1iWCl4)


How does it work?

⏰ The trigger runs every day at 7AM.

📅 Your Google Calendar is checked.

🔢 If there are events or meetings, a number > 0 is returned. Otherwise, it's 0.

📝 A text message is generated with a summary of all your events, including all relevant details.

❌ If no events are found, a "no event" message is sent.
