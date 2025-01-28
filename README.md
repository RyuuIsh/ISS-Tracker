# ISS-Tracker-&-Notifier
The ISS Tracker & Notifier is a Python-based application that checks if the International Space Station (ISS) is overhead and whether it's night at your location. If both conditions are true, it sends an email notification, encouraging you to look up and spot the ISS in the sky!

## Features
1. Real-Time ISS Tracking
- Uses the Open Notify ISS API to track the current latitude and longitude of the ISS.
2. Day/Night Detection
- Uses the Sunrise-Sunset API to determine whether it's currently nighttime at your location.
3. Email Notifications
- Sends an email to notify you when the ISS is visible overhead during nighttime.
4. Automated Checks
- Runs every minute to ensure you're notified whenever the conditions are met.

## Working
1. The app fetches the current ISS location from the API.
2. Checks if the ISS is within ±5° of your latitude and longitude.
3. Fetches sunrise and sunset times for your location to determine if it's night.
4. If both conditions are met, an email is sent to notify you.

## Technologies Used
- Python: Core programming language.
- Requests: For making HTTP requests to APIs.
- SMTP: For sending email notifications.
- Datetime: For handling and comparing time.

## Ideas for Future Enhancements
- Add a GUI interface for easier setup.
- Integrate a weather API to check for clear skies.
- Add support for sending notifications via SMS or push notifications.

Stay connected to the cosmos with this ISS Tracker & Notifier and never miss a chance to spot the International Space Station! 🚀✨
