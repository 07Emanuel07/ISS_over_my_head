# ISS Over My Head Project

This Python application monitors the position of the International Space Station (ISS) and sends an email notification when the ISS is overhead and it is dark outside.

## Key Features

**API Integration for ISS Position:**
  - The application uses the Open Notify API to get the current position of the ISS. It checks if the ISS is within a specified range of the user's latitude and longitude.

**Sunrise and Sunset API:**
  - The application uses the Sunrise-Sunset API to determine the sunrise and sunset times for the user's location. This helps to check if it is currently night.

**Email Notification System:**
  - The application sends an email notification when the ISS is overhead and it is currently dark. It uses the `smtplib` library to send emails via Gmail.

**Continuous Monitoring:**
  - The application runs in a loop, checking every minute to see if the ISS is overhead and if it is night, ensuring timely notifications.
