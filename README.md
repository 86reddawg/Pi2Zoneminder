Pi2Zoneminder
=============

Trigger Zoneminder recording from Pi connected PIR/door sensors

This project uses a piface board that is wired to all of the existing home security sensors (magnetic door sensor, PIR, etc)  The factory home alarm runs on 12VDC and includes a battery backup, so the charging system was left inplace.  A vehicle phone charger/adapter was used to power the pi and provide whetting voltage to the dry-style factory alarm contacts.  The factory PIR sensors are powered by 12V, but contacts are seperate.  The end result is a battery backed system that reliably determines states of all doors and motion.

This script sends motion detection to ZoneMinder and allows it to trigger through pi detection rather than needing lots of processing power for motion detection through image processing (very taxing with multiple HD cameras)
