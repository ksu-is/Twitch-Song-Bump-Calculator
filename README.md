# Twitch-Song-Bump-Calculator
A python program with a GUI to track incoming subscriptions, bits, and donations for a single Twitch stream session to calculate priority song requests for a music stream. 

I volunteer as a moderator for a Twitch music channel, and would like to create a program to track the monetary value of subscriptions, bits, and donations that come in for a singular stream. We prioritize song requests by order of largest value, so pulling this information automatically, or minimally by hand, would be very useful. Subscriptions come in different tiers, and we require 2 gifted subs, or Tier 2+ for a bump, 500 bits, or $5 donation, so there would be a minimum threshold to attain for each user. Currently, I have a Google Sheet where I manually type data in to calculate everything but having a program to calculate all of that while providing me a printed statement of the totals to copy and paste into the notes for the song request would be ideal. 
For this, I’d like to create a similar program to the KSU grade scraper to collect information. I noticed that there is an activity feed URL with a list of all the subscriptions and bits coming in. I think the issue with scraping this information would be how to make it reset for each stream. I think a manual reset and a manual way to insert information would be best. 
Ideally, some sort of GUI could be made, like the calculator project, for manual entry and a display for the session’s donations and donators. 

Alternative: If I am not able to do a real-time or refreshed-based updated list, I think taking my Google Sheet and creating a fancy GUI calculator would be an upgrade. 
Extra: If I could get this to be shared with other moderators, maybe through a Google Sheet file, or something similar, that would be an added bonus.

Inspirational Projects:

Twitch Livestream Data Scraper by thomasglauser

•	https://ai.plainenglish.io/how-i-built-a-twitch-data-scraper-that-runs-every-15-minutes-with-python-playwright-7c80a5982d7e
•	https://github.com/thomasglauser/Twitch-Livestream-Data-Scraper

This one scrapes information from a Twitch Stream and creates a Google Sheet. I like that it returns the starting timestamps which can be useful for logging separate streams, refreshes, and that it exports information to a Google Sheet, which can definitely be shared with other moderators.

Twitch_Hue by batubozhan

•	https://github.com/batubozkan/twitch_Hue

This code takes the donation information and depending on the amount, outputs a color to a Phillips Hue lamp. I know this one is in Javascript, but it does give me ideas on how to format the minimum threshold for bumping a song request.

TwitchStreaker by BrainInBlack

•	https://github.com/BrainInBlack/TwitchStreaker

This program is more of a subscription and goal tracker for Twitch streams, but I like how it defines the donation variables with points to add up everything.  
